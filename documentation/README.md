# **Pawsome Strolls**

The Pawsome Scrolls site is designed as a responsive website allowing users to access it on various devices ranging from a mobile phone to a desktop screen. 

 The site is aimed to target people who own dogs and are looking to hire someone to care for their pet and take them out for exercise. The various sections on the page allow the potential customer to find out about the services offered and formats in which to contact the service provider. 

[View the site from here.](https://chandni-l5.github.io/pawsome-strolls/)

![Responsive Mockup](documentation/responsive%20shot.jpg)

## Table of Contents  
1. [User Experience](#user-experience)
2. [Design](#design)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Deployment & Local Development](#deployment-&-local-development)
6. [Testing](#testing)
7. [Credits](#credits)

## 1. User Experience
The website is created on behalf of the service provider. Jenny's aim is to secure enquiries in order to arrange bookings with interested parties. 

The site provides information about Jenny, the services she provides and testimonials from previous clients. There is also a function to complete an enquiry form in order for the service provider to reach out to the enquirer. 

### 1.1 User Stories
#### Client Goals 
- To be able to view the site on a range of device sizes.
- Proof of credentials to determine if the provider is qualified for the role.
- An easy-to-use format for submitting enquiries or accessing contact information. 

#### Potential Client Goals 
- I want to view high quality images and engaging testimonials of previous clients.
- I want to view the areas where the service is available.
- I want to find their social media profiles.

#### Returning Client Goals
- As a returning customer, I want access to discounts or special offers.
- I want to be able to easily navigate across the site to find relevant sections of information.
- I want to quickly access the enquiry form to submit my query.


I have utilised the Projects function on my repository to keep track of the user stories that apply to this site. The user stories are recorded along with the acceptance criteria and tasks required to meet this goal. The stories are organised into sections of progress and allow me to keep track of where I am at throughout the development process. 
![Project card from github](/documentation/project%20goals%201.png)

In addition each goal has been catagorised in terms of priority - must haves, should haves and could haves. This allows me to target those highest in priority to ensure I can meet the necessary functions of the site. 
![Project board from github](/documentation/project%20goals%202.png)

## 2. Design
### 2.1 Colour Scheme
I used [mycolor.space](https://mycolor.space/) to create a colour pallette to apply to the site. I applied the hex color code #5e8697 as the initial colour for the background of the page and added this to mycolor.space to generate a colour pallette. 

![blocks of colours with hex color codes and color names](/documentation/color-pallette.png)

### 2.2 Typography
[Google fonts](https://fonts.google.com/) are used to apply the following fonts:

Arvo - Which is used for the page title, navigation bar items, headings and some small sections of text throughout the site.
![Image of Arvo font(text: Pawsome Scrolls)](/documentation/arvo%20font.png) 

Lato - Which is used for larger sections of text.
![Image of Lato font(text: Pawsome Scrolls)](/documentation/lato%20font.png)

[Font Awesome](https://fontawesome.com/) is used for the use of icons in various parts of the site such as the nav bar and footer.

### 2.3 Imagery
All of the images used throughout the site were sourced from [pexels.com](https://www.pexels.com/). Images from this source are liscensed for free use. I also used [befunky.com](https://www.befunky.com/dashboard/) to resize the images.

### 2.4 Wireframes
I used Balsamiq to create wireframes to help me visualise the layout of the site. Wireframes for mobile, tablet and desktop were created. I kept the user stories and goals in mind when designing the layout. 

[Index Page Wireframe](/documentation/wireframes.jpg)

[Enquiry Form and Success Wireframes](/documentation/wireframes%202.png)

## 3. Features
The website consists of three pages, two are accessible from the navigation bar/menu. The first page contains all the general information, the second page contains the enquiry form and the third page consists of a thank you/ confirmation of success when submitting the enquiry form on the second page. 

I have used Bootstrap V5.3 throughout the website and much of the code is implemented. 

### 3.1 General Features 
#### 3.1.1 All Pages
##### Navigation
All three pages contain a responsive navigation bar and menu at the top of the page. I have used to Bootstrap to implement the navbar as the skeleton code. The left side consists of a logo and title of the page - Pawsome Strolls - both are selectable and navigate the user back to the homepage. The right side of the nav bar contains links to various sections of the homepage and ends with an outlined button linking to the enquiry page. 

![Image of navbar in viewport 1044+](/documentation/navbarext.png)

 To improve user experience and minimise overcrowding of the nav bar - on viewports of 768px and less the menu aspect of the navbar minimises into the burger button, where the menu items are accessed by selecting the icon, and on viewports of 320px and less the title of the page appears slightly smaller to fit comfortably within the navbar. The burger icon is used as its a commonly used icon for this function on other sites and provides familiarity for users.

 The navbar is fixed to the top of the page and remains in position when scrolling up or down throughout any of the pages. 

 ![Image of navbar in viewport 320](/documentation/navbar320.png)

##### Footer 
The footer is split into two sections, the first containing the contact details and the second containing icon links to social media. The icons have been used again to provide familiarity for the users as these are commonly used and to provide a clean and tidy footer. I have used the grid layout, code and styling taken from Bootstrap.

![Image of the footer in viewport 1044](/documentation/footer1044.png)

The footer is responsive between viewports greater than 1044px and less than 768px. This difference is applied to avoid overcrowding in the footer and to maintain the tidiness. 

The footer is positioned at the base of the page and becomes visible once all of the main content of the page is viewed.

![Image of the footer in viewport 768](/documentation/footer768.png)

#### 3.1.2 Index Page
The index page contains the main content of the website and is split into sections. Some of the sections also contain an enquiry button that links the user directly to the enquiry form. The button is mirrored in style to the button in the navigation bar and also has an interactive function to make it standout from the rest of the content.

##### Image Carousel 
The main content of the website is provided on the homepage. The initial section of the page consists of a carousel of images of the service provider Jenny, in various locations walking individual and groups of dogs.

 The carousel is set to autoplay and rotates images every few seconds, there are also some navigation arrows to rotate the images at will. The carousel is responsive and reduces in size as the size of the viewport reduces.

[![Image from Gyazo](https://i.gyazo.com/17bbe66d9a44c43a57bf9a8c22505428.gif)](https://gyazo.com/17bbe66d9a44c43a57bf9a8c22505428)

##### About Me 
The About Me section consists of a grid layout containing a section of text, and image and a smaller grid containing some information cards. This area is responsive and the display changes as the screen size gets smaller to ensure the content is easily viewable without overcrowding the screen. 

![About me section](/documentation/about-me.png)

The About Me section concludes with an 'Enquire now' button. The styling of the button mirrors the button from the navbar and is also interactive where it changes colour when hovered over. 

##### Services
The Services section implements a card layout using Bootstrap. Each card contains an image or video, a heading and some information text.

Each card outlines the set-up of the sessions, the timing of the session and some information about what to expect. It also includes a price point in bold text and outlined to seperate from the main body of text. 

The final two cards bullet point a number of locations where the service is available and also displays the offers and discounts.

The locations card also contains a placeholder for a video where it can be controlled by pausing and playing and the audio from the video is muted when the page is loaded and must be un-muted manually.

The whole section is reponsive and the cards will shift depending on the screen size for ease of viewing.

![Services section](/documentation/services.png)

The Services section is concluded again with an 'Enquire now' button in the same format.

##### Testimonials
The Testimonials section mirrors the format of the cards applied in the services section. This is to enhance user experience by matching the conformity of the page. There are 6 testimonials provided. The layout of the card consists of an image and some text. The cards are ordered by the orientation of the image within. In addition the cards are responsive and the layout shifts as the size of the screen reduces. 

As per the previous section, the testimonials are reponsive and the cards will shift depending on the screen size for ease of viewing. In addition the section is again concluded with the enquiry button. I have opted to place this button at the end of each section due to one of the returning client goals, allowing the user to access the enquiry form quickly and easily. 

![Testimonials Section](/documentation/testimonials.png)

#### 3.1.3 Enquiry Form Page
The enquiry form is situated in a seperate page and can be accessed by any of the enquiry buttons on the homepage or within the navigation menu.

The page is titled with a header in bold text . There is a small line of text providing instructions of how to proceed. The sections of the form has been implemented using bootstrap. The form contains fields for the name of the client, email address, contact number, client's dog's name, a dropdown of the services and a text area field for enquiry details. The user can submit the form selecting the 'Submit Form' button, which is also styled with the same theme but different colours to the enquiry button on the homepage. Users must complete each field in order for the form to be submitted and there is a tooltip that appears if a field is incomplete. 

![Enquiry form page](/documentation/enq%20form.png)

#### 3.1.4 Success Page
The Success Page is accessed upon the successful completion and submission of the form on the Enquiry Page. The purpose of this page is to confirm to users that their form has been successfully submitted. Additionally, this page includes a brief thank-you message and details about what to expect next with a follow-up timeline and also provides contact details if the client wishes to submit any further information.

![Success Page](/documentation/success.png)

### 3.2 Future Implementations
Due to time constraints I was unable to action all of the user goals. As I had catagorised the stories I ensured that all of the 'must-have' tasks have been completed. 

In future implementations I would create a seperate section for the Locations topic and also include an interactive map function. 

I would also consider create seperate pages for each section and include a bit more content. I believe this would improve user experience as it would simplify the content on each page and they would not need to view content of the other sections at the same time on larger viewports. 

Another feature I would consider adding would be a 'back to top' function on the homepage using javacript.

### 3.3 Accessibility

During the designing and styling process of the website, I have kept in mind to aim to make the page as user friendly and accessible as possible. I have achieved this by: 
- Semantic HTML 
-Use of descriptive alt attributes on the images and videos used throughout the site. 
-I have checked the colour scheme used on the page using [WebAIM](https://webaim.org/resources/contrastchecker/) to check the colour contrast. 
![screenshot of colour contrast check](/documentation/color%20contrast.png)
-I have also used the chrome extension [Web Disability Simulator](https://chromewebstore.google.com/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) to also consider the visuals of the page and contrast between the content for users with visual impairments.
- Added aria-labels to allow screen readers to understand the current pages.
- Use of a Sans Serif font alternative.
-Use of the hover function on all buttons across the site and use of a uniform style to make it clear that this is a button.
[![Image from Gyazo](https://i.gyazo.com/d7a0a1a62e4915471a41775fe399aa15.gif)](https://gyazo.com/d7a0a1a62e4915471a41775fe399aa15))

## 4. Technologies Used
### 4.1 Languages used 
- HTML
- CSS
- Javascript (via Bootstrap version 5.3)

### 4.2 Frameworks, Libraries & Programs Used
- Balsamiq - to create wireframes 
- Git - For version control and deployment 
- Github - used as the code editor and save files
- Bootstrap version 5.3 - Code for the navigation bar, carousel, cards and form have been used and amended for use. CSS styling was also used and modified from Bootstrap using the documentation and some JavaScript has been applied to assist the functionality of the bootstrap code and CSS
- Google Fonts -  to implement the fonts used in the site
- Font Awesome - for icons and logos used in the site
- Chrome dev tools - To test and troubleshoot various features and also test responsiveness of the pages 
- [Pexels.com](https://www.pexels.com/) - To source the images used in the site
- [Befunky](https://www.befunky.com/dashboard/) - to resize and alter the images
- [Tinypng](https://tinypng.com/) - To compress images
- [Cloudconvert](https://cloudconvert.com/jpg-to-webp) - to convert images to different file types. 
- [Favicon.io](https://favicon.io/emoji-favicons/) - to create an emoji favicon
- [Amiresponsive](https://ui.dev/amiresponsive) - to show the website on a range of device screens

## 5. Deployment  

The website is deployed using GitHub Pages. To Deploy the site using GitHub Pages:

1. Login (or signup) to Github.
2. Go to the repository for this project - [Pawsome Strolls](https://github.com/Chandni-L5/pawsome-strolls)
2. Click the settings button.
3. Select pages in the left hand navigation menu.
4. From the source dropdown select 'Deploy from a branch' and in the branch dropdown select 'main' and press save.
5. The site has now been deployed.
6. When returning to the code page in the repository a Deployments section will appear in the right side column - this process may take a few minutes before the site goes live. The deployed sight can be accessed via this link.

## 6. Testing
### 6.1 Manual Testing
Testing the site has been an ongoing process throughout the development of the website. I have used Chrome dev tools to review and troubleshoot issues as build has progressed.  

A number of issues were identified throughout this process and fixed simultaenously: 

- Initially when I downloaded the images to be used on the site, I added these straight to the website however on reviewing I realised that the images were all different sizes and this created issues with the functioning of the carousel and also just the general layout of the page. 

After discussing with my mentor Mortiz Wach I resized the images to an equal size. In addition with the support of tutor assistance I was advised to move some of the styling which was included in the bootstrap to the CSS stylesheet and apply a 100% variable to the width of every image, in order for it to fit within its container. This resolved the issues with the functionality of the carousel where the image was enlarging when moving to the next image.

- When creating the mini cards within the the 'about me' section, I was struggling to centre the content within the `div` as I was unsure how to target it.

![screenshots of mini card](/documentation/card%20issue.png) ![screenshots of mini card](/documentation/card%20issue%202.png)

 I requested some assistance from a fellow student Ivan Kimpl who advised me to apply a `flex` variable to the `display` property and target the `col` class, I could then apply other properties to ce`nter the content and fix this issue.

- The navigation bar would dissappear when scrolling down to the content. To fix this I reviewed the Bootstrap documentation, to find out if there was already a selector in place to add to the element and identified that by added the class `fixed` I would be able to fix the nav bar to the top of the page regardless of the where on the rest of the page I was at. 

- By fixing the navbar this created another issue. The navbar now overlapped the carousel at the top of the homepage and when automatically scrolling to the nav-links the navbar would overlap the header of the sections of the homepage. 

I discussed this issue with my mentor who suggest to look into the the `scroll-padding-top` property. However when trying to implement this I found that the issue was still occuring. Whilst searching on stack overflow and google for a possible solution, I also decided to reach out to other collegues on slack. Working togethor with an alumni student Vernell Clarke, who assisted me to identify where to apply a fix. By applying an `id` to an invisible `div` above the headers, and applying the property of `padding-top` and `margin-top`, and using dev chrome tools I was able to adjust the headers into the right place so that when the navlink was selected the page would scroll automatically to the top of the header.  

- When manually checking the navlinks from the enquiry page and success page, I identified that when selecting the link from a mobile viewport the link would not land at the correct place above the header. I checked all of the code and compared this using [diffchecker](https://www.diffchecker.com/) however could not identify any reason why this was not working. 

I discussed this issue again with Vernell Clarke and asked him to manually check and test out the site to see if the issue was also occuring from his end. We identified that this issue was only occuring in Google Chrome, however when testing on Safari and Mozilla Firefox that the site was functioning as expected and so I deduced that there may be some bug with the chrome dev tool when viewing the site in this viewport. 

- When scrolling through the homepage, I decided to add a `border-radius` to the images on the page. This was implemented to apply conformity with the other shapes of the cards on the page.

- I also identified that some of the price points on the services cards were not of identical shape and size. I implemented some further styling to the size of this section. As the 'Puppy Walks' card only contains 1 line of text, the text automatically positions at the top line of that shape.
![screenshot of services prior to fix](/documentation/services%20prefix.png)

 To enhance the visual appearance of this card, I specifically targeted the `id` and the `strong` element to isolate the text. I applied a `position: relative` property and adjusted the `top` value to refine its positioning. I used dev chrome tools to adjust the `px` to ensure the text was in the correct position. Finally I checked this through different viewports and applied adjustments in the `media query`.

 ![screenshot of services post fix](/documentation/services%20fixed.png)

- During the final testing of the site, I identified that the hover function of the 'enquire now' button was not functionining and when selecting the button there was no proceeding action. Using dev chrome tools, I identified that the margin of the div below the button was creating an overlap and the button was layered below this invisible div. 
[![Image from Gyazo](https://i.gyazo.com/19896f7d212908a3206e54332c2a4e63.gif)](https://gyazo.com/19896f7d212908a3206e54332c2a4e63)
![dev chrome tools applied to the relevant section](/documentation/enq%20button%20fix.png)

To fix this issue I applied z-index property to the relevant css selectors to ensure the priority of the enquiry button and hover function sat at the top.

[![Image from Gyazo](https://i.gyazo.com/d7a0a1a62e4915471a41775fe399aa15.gif)](https://gyazo.com/d7a0a1a62e4915471a41775fe399aa15)


### 6.2 Lighthouse
### 6.3 Validation

## 7. Credits
### 7.1 Code Used
### 7.2 Content
### 7.3 Media
### 7.4 Acknowledgments

