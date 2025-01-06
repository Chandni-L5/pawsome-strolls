## 6. Testing

### 6.1 Testing User Stories
#### Testing Client Goals 
##### Goal: To be able to view the site on a range of device sizes.
 Result- ✔ - The site is responsive on a number of browsers and devices. 

##### Goal: Proof of credentials to determine if the provider is qualified for the role.
Result - ✔ - This goal has not been fully achieved however within the content of the 'About Me' section. On future implementations I would include a separate section or some imagery to account for the qualifications of the service provider.

##### Goal: An easy-to-use format for submitting enquiries or accessing contact information. 
Result - ✔-  Simple and straightforward form provided on a separate page and once submitted successfully the user is directed to a page that displays a thank you message confirming the form is submitted.


#### Potential Client Goals 
##### Goal: I want to view high quality images and engaging testimonials of previous clients. 
Result - ✔ - The website contains a number of high quality images and a dedicated section displaying testimonials.

##### Goal: I want to view the areas where the service is available.
Result  - ✔ - The locations covered are displayed within the services section. On a future implementation I would consider making a separate section or page and display the locations covered including a map or some kind of visual aid.

##### Goal: I want to find their social media profiles.
Result - ✔ - The links to social media are located in the footer of the page and once selected open the site on a separate tab.

#### Returning Client Goals
##### Goal: As a returning customer, I want access to discounts or special offers.
Result - ✔ - Discounts and offers can be found in the services section. In future implementations I would consider creating a separate link to the discounts and offers from the navigation menu or alternatively have the services section displayed on a separate page and to have the discounts and offers card displayed more prominently.

##### Goal: I want to be able to easily navigate across the site to find relevant sections of information.
Result - ✔ - The website has a fully functioning navigation bar that is visible at all times whilst browsing the page. When a menu item is selected, the page automatically scrolls to the relevant section or to the relevant page. 

##### Goal: I want to quickly access the enquiry form to submit my query.
Result - ✔ - The enquiry form is accessible from a number of locations throughout the site and the button is highlighted with a unique style to make it stand out from the rest of the content. 

### 6.2 Fixing Bugs
Testing the site has been an ongoing process throughout the development of the website. I have used Chrome dev tools to review and troubleshoot issues as build has progressed.  

A number of issues were identified throughout this process and fixed simultaneously: 

- Initially when I downloaded the images to be used on the site, I added these straight to the website however on reviewing I realised that the images were all different sizes and this created issues with the functioning of the carousel and also just the general layout of the page. 

After discussing with my mentor Mortiz Wach I resized the images to an equal size. In addition with the support of tutor assistance I was advised to move some of the styling which was included in the bootstrap to the CSS stylesheet and apply a 100% variable to the width of every image, in order for it to fit within its container. This resolved the issues with the functionality of the carousel where the image was enlarging when moving to the next image.

- When initially implementing my running some of the colours used through the contrast checker, the grey and dark blue blackground generated a score of 5.64:1. This combination failed in the class of WCAG AAA - [see here](https://webaim.org/resources/contrastchecker/?fcolor=9B9D9E&bcolor=222529). After discussing with my mentor Moritz, he advised to try to achieve a higher score and have a pass mark in all classes and so the light grey color was altered. 

![Contrast check on final colours](/documentation/contrast%20checker.png)

- When creating the mini cards within the the 'about me' section, I was struggling to centre the content within the `div` as I was unsure how to target it.

![screenshots of mini card](/documentation/card%20issue.png) ![screenshots of mini card](/documentation/card%20issue%202.png)

 I requested some assistance from a fellow student Ivan Kimpl who advised me to apply a `flex` variable to the `display` property and target the `col` class, I could then apply other properties to center the content and fix this issue.

- The navigation bar would disappear when scrolling down to the content. To fix this I reviewed the Bootstrap documentation, to find out if there was already a selector in place to add to the element and identified that by added the class `fixed` I would be able to fix the nav bar to the top of the page regardless of the where on the rest of the page I was at. 

- By fixing the navbar this created another issue. The navbar now overlapped the carousel at the top of the homepage and when automatically scrolling to the nav-links the navbar would overlap the header of the sections of the homepage. 

I discussed this issue with my mentor who suggest to look into the the `scroll-padding-top` property. However when trying to implement this I found that the issue was still occuring. Whilst searching on stack overflow and google for a possible solution, I also decided to reach out to other colleagues on slack. Working together with an alumni student Vernell Clarke, who assisted me to identify where to apply a fix. By applying an `id` to an invisible `div` above the headers, and applying the property of `padding-top` and `margin-top`, and using dev chrome tools I was able to adjust the headers into the right place so that when the navlink was selected the page would scroll automatically to the top of the header.  

- When manually checking the navlinks from the enquiry page and success page, I identified that when selecting the link from a mobile viewport the link would not land at the correct place above the header. I checked all of the code and compared this using [diffchecker](https://www.diffchecker.com/) however could not identify any reason why this was not working. 

I discussed this issue again with Vernell Clarke and asked him to manually check and test out the site to see if the issue was also occurring from his end. We identified that this issue was only occurring in Google Chrome, however when testing on Safari and Mozilla Firefox that the site was functioning as expected and so I deduced that there may be some bug with the chrome dev tool when viewing the site in this viewport. 

- When scrolling through the homepage, I decided to add a `border-radius` to the images on the page. This was implemented to apply conformity with the other shapes of the cards on the page.

- I had decided to include a separate card within the services section to highlight the benefits of a walk for a dog. This card includes an AI video. Initially I downloaded the video as an mp4 and reduced the size of the video to fit 400x300px however realised this distorted the quality of the video. I then reverted back to the original size and compressed the mp4 file and added to the site. When running the site through the port the video was showing on the site however when pushing through to deployment I was getting a 401 error on the page for the video and neighbouring locations jpg image and they were not loading. 
![screenshot of site error](/documentation/image%20and%20video%20error.png)

I decided to convert the jpg file to webp as per the other images on the page and also converted the mp4 file to webm using [freeconvert.com](https://www.freeconvert.com/). When replacing the faulty files and pushing through, this resolved the 401 error issue and both image and video can now be loaded on the website.
![screenshot of fix](/documentation/image%20and%20video%20fixed.png)

- I also identified that some of the price points on the services cards were not of identical shape and size. I implemented some further styling to the size of this section. As the 'Puppy Walks' card only contains 1 line of text, the text automatically positions at the top line of that shape.
![screenshot of services prior to fix](/documentation/services%20prefix.png)

 To enhance the visual appearance of this card, I specifically targeted the `id` and the `strong` element to isolate the text. I applied a `position: relative` property and adjusted the `top` value to refine its positioning. I used dev chrome tools to adjust the `px` to ensure the text was in the correct position. Finally I checked this through different viewports and applied adjustments in the `media query`.

 ![screenshot of services post fix](/documentation/services%20fixed.png)

- During the final testing of the site, I identified that the hover function of the 'enquire now' button was not functioning and when selecting the button there was no proceeding action. Using dev chrome tools, I identified that the margin of the div below the button was creating an overlap and the button was layered below this invisible div. 
[![Image from Gyazo](https://i.gyazo.com/19896f7d212908a3206e54332c2a4e63.gif)](https://gyazo.com/19896f7d212908a3206e54332c2a4e63)
![dev chrome tools applied to the relevant section](/documentation/enq%20button%20fix.png)

To fix this issue I applied z-index property to the relevant css selectors to ensure the priority of the enquiry button and hover function sat at the top.

[![Image from Gyazo](https://i.gyazo.com/d7a0a1a62e4915471a41775fe399aa15.gif)](https://gyazo.com/d7a0a1a62e4915471a41775fe399aa15)

### 6.3 Manual Testing 

#### Site function testing
Full testing has been completed on the following devices: 
- Laptop: Macbook Air M3 2024
- Mobile: iPhone 15 

The browsers used to test the site include:
- Google Chrome
- Safari
- Mozilla Firefox 

Additional testing was also carried out by a colleague on a variety of browsers on a laptop and they had reported no issues. 

![Screen shot of testing table](/documentation/testing.png) 
[Click here to enlarge the above image](/documentation/testing.png)

Most of the testing of the various functions of the site were successful! One issue has been noted when viewing the site via Mozilla Firefox - the carousel only plays automatically when the browser is not selected on the laptop viewport. However on a different occasion when checking again I have identified that the carousel is functioning on this browser and no change is required to be implemented.

I have also submitted the site for peer review on slack and one tester identified that there was an issue with the size and layout of the mini-cards of the 'About Me' section on their laptop.

![screen shot of image provided by a tester from peer review](/documentation/peer%20review.png)

I was unable to replicate this issue on my devices and so unable to resolve. 

### 6.4 Lighthouse
I have used Lighthouse within Chrome dev tools to test the performance, accessibility and best practices. I have checked both both device types of Mobile and Desktop.

![Lighthouse results](/documentation/lighthouse%20poor.png)
![Lighthouse details of poor results](/documentation/lighthouse%20issues.jpg)
On initial checks the performance levels were slightly low. 

I was able to improve the above score by resizing the images on the page and changed them to webp files. 

On final checks the scores are greatly improved for both desktop and mobile options. 

![Lighthouse improved results desktop](/documentation/lighthouse%20100.png)

### 6.5 Validation
#### 6.5.1 W3C HTML and CSS 
[W3C](https://validator.w3.org/) validator has been used to check the HTML on each of the pages of the website and the css stylesheet.

##### HTML
[index.html](https://chandni-l5.github.io/pawsome-strolls/index.html) 
The initial check highlighted a few issues with the code. These issues have now been addressed.
![error in html validator](/documentation/html%20checker.jpg)
On final check, only one warning message remained:
[See here](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fchandni-l5.github.io%2Fpawsome-strolls%2F)


[enquiry.html](https://chandni-l5.github.io/pawsome-strolls/enquiry.html)
The HTML code of the enquiry page passed successfully. 
![html validation for enquiry page](/documentation/html%20validator%20success.png)

[success.html](https://chandni-l5.github.io/pawsome-strolls/success.html)
The HTML code of the success page passed successfully.
![html validation for success page](/documentation/html%20validator%20success.png)

##### CSS 
![successful css validator](/documentation/css%20validator.png)

#### 6.5.2 Autoprefixer CSS
I have used [Autoprefixer](https://autoprefixer.github.io/) to add vendor prefixes to the CSS.