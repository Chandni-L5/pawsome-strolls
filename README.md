# **Pawsome Strolls**

The Pawsome Strolls site is designed as a responsive website allowing users to access it on various devices ranging from a mobile phone to a desktop screen. 

 The site is aimed to target people who own dogs and are looking to hire someone to care for their pet and take them out for exercise. The various sections on the page allow the potential customer to find out about the services offered and formats in which to contact the service provider. 

[View the site from here.](https://chandni-l5.github.io/pawsome-strolls/)

![Responsive Mockup](/documentation/responsive%20shot.png)

## Table of Contents  
1. [User Experience](#user-experience)
   
    1.1 [User Stories](#11-user-stories)
2. [Design](#design)

    2.1 [Colour Scheme](#21-colour-scheme)

    2.2 [Typography](#22-typography)

    2.3 [Imagery](#23-imagery)

    2.4 [Wireframes](#24-wireframes)
3. [Features](#features)

    3.1 [General Features](#31-general-features)  

    3.1.1 [All Pages](#311-all-pages)

    3.1.2 [Index Page](#312-index-page)

    3.1.3 [Enquiry Form Page](#313-enquiry-form-page)

    3.1.4 [Success Page](#314-success-page)

    3.2 [Future Implementations](#32-future-implementations)

    3.3 [Accessibility](#33-accessibility)
4. [Technologies Used](#technologies-used)

    4.1 [Languages used](#41-languages-used)

    4.2 [Frameworks, Libraries & Programs Used](#42-frameworks-libraries--programs-used)

5. [Deployment & Local Development](#deployment-&-local-development)
6. [Testing](/documentation/testing.md)
7. [Credits](#credits)

    7.1 [Code Used](#71-code-used)

    7.2 [Content](#72-content)

    7.3 [Media](#73-media)

    7.4 [Documentation and Testing](#74-documentation-and-testing)

    7.5 [Acknowledgements](#75-acknowledgments)

## 1. User Experience
The website is created on behalf of the service provider. Jenny's aim is to secure enquiries in order to arrange bookings with interested parties. 

The site provides information about Jenny, the services she provides and testimonials from previous clients. There is also a function to complete an enquiry form in order for the service provider to reach out to the enquirer. 

The target audience for this site are local dog owners who could be working full time or seeking services if they are unable to walk their dogs on a regular basis.

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
I used [mycolor.space](https://mycolor.space/) to create a colour palette to apply to the site. I applied the hex color code #5e8697 as the initial colour for the background of the page and added this to mycolor.space to generate a colour palette. 

![blocks of colours with hex color codes and color names](/documentation/color-pallette.png)

### 2.2 Typography
[Google fonts](https://fonts.google.com/) are used to apply the following fonts:

Arvo - Which is used for the page title, navigation bar items, headings and some small sections of text throughout the site.
![Image of Arvo font(text: Pawsome Scrolls)](/documentation/arvo%20font.png) 

Lato - Which is used for larger sections of text.
![Image of Lato font(text: Pawsome Scrolls)](/documentation/lato%20font.png)

[Font Awesome](https://fontawesome.com/) is used for the use of icons in various parts of the site such as the nav bar and footer.

### 2.3 Imagery
All of the images used throughout the site were sourced from [pexels.com](https://www.pexels.com/). Images from this source are licensed for free use. I also used [befunky.com](https://www.befunky.com/dashboard/) to resize the images. 

The video used in the services section to highlight the benefits of a walk was created using [invideo AI](https://invideo.io/). I created a customed script and my fellow student Ivan Kimpl created this custom video using his account with invideo AI.

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

#### Introductory Title and Message
The first part of the page consists of `div` cotaining the title of the page and an small introductory sentence to introduce the main purpose of the website. The placement of this section allows the user to immediately understand the purpose thus fufil the primary goal.

![Screenshot of intro message and carousel](/documentation/intro-title.png)

##### Image Carousel 
The main content of the website is provided on the homepage. The initial section of the page also consists of a carousel of images of the service provider Jenny, in various locations walking individual and groups of dogs.

 The carousel is set to autoplay and rotates images every few seconds, there are also some navigation arrows to rotate the images at will. The carousel is responsive and reduces in size as the size of the viewport reduces.

![Image from Gyazo](/documentation/carousel-gif.gif)

##### About Me 
The About Me section consists of a grid layout containing a section of text, and image and a smaller grid containing some information cards. This area is responsive and the display changes as the screen size gets smaller to ensure the content is easily viewable without overcrowding the screen. 

![About me section](/documentation/about-me.png)

The About Me section concludes with an 'Enquire now' button. The styling of the button mirrors the button from the navbar and is also interactive where it changes colour when hovered over. 

##### Services
The Services section implements a card layout using Bootstrap. Each card contains an image or video, a heading and some information text.

Each card outlines the set-up of the sessions, the timing of the session and some information about what to expect. It also includes a price point in bold text and outlined to separate from the main body of text. 

The final three cards bullet point a number of locations where the service is available, the benefits of a walk for a dog and also displays the offers and discounts.

The benefits card also contains an AI video showcasing some fun clips of dogs being walked and playing and also includes a voiceover of the benefits of a walk for a dog. This is also summarised in the text content below the video.

The whole section is responsive and the cards will shift depending on the screen size for ease of viewing.

![Services section](/documentation/services-responsive.png)

The Services section is concluded again with an 'Enquire now' button in the same format.

##### Testimonials
The Testimonials section mirrors the format of the cards applied in the services section. This is to enhance user experience by matching the conformity of the page. There are 6 testimonials provided. The layout of the card consists of an image and some text. The cards are ordered by the orientation of the image within. In addition the cards are responsive and the layout shifts as the size of the screen reduces. 

As per the previous section, the testimonials are responsive and the cards will shift depending on the screen size for ease of viewing. In addition the section is again concluded with the enquiry button. I have opted to place this button at the end of each section due to one of the returning client goals, allowing the user to access the enquiry form quickly and easily. 

![Testimonials Section](/documentation/testimonials.png)

#### 3.1.3 Enquiry Form Page
The enquiry form is situated in a separate page and can be accessed by any of the enquiry buttons on the homepage or within the navigation menu.

The page is titled with a header in bold text . There is a small line of text providing instructions of how to proceed. The sections of the form has been implemented using bootstrap. The form contains fields for the name of the client, email address, contact number, client's dog's name, a dropdown of the services and a text area field for enquiry details. The user can submit the form selecting the 'Submit Form' button, which is also styled with the same theme but different colours to the enquiry button on the homepage. Users must complete each field in order for the form to be submitted and there is a tooltip that appears if a field is incomplete. 

![Enquiry form page](/documentation/enq%20form.png)

#### 3.1.4 Success Page
The Success Page is accessed upon the successful completion and submission of the form on the Enquiry Page. The purpose of this page is to confirm to users that their form has been successfully submitted. Additionally, this page includes a brief thank-you message and details about what to expect next with a follow-up timeline and also provides contact details if the client wishes to submit any further information.

![Success Page](/documentation/success.png)

### 3.2 Future Implementations
Due to time constraints I was unable to action all of the user goals. As I had catagorised the stories I ensured that all of the 'must-have' tasks have been completed. 

In future implementations I would create a separate section for the Locations topic and also include an interactive map function. 

I would also consider create separate pages for each section and include a bit more content. I believe this would improve user experience as it would simplify the content on each page and they would not need to view content of the other sections at the same time on larger viewports. 

Another feature I would consider adding would be a 'back to top' function on the homepage using JavaScript.

### 3.3 Accessibility

During the designing and styling process of the website, I have kept in mind to aim to make the page as user friendly and accessible as possible. I have achieved this by: 
- Semantic HTML 
-Use of descriptive alt attributes on the images used throughout the site. 
-I have checked the colour scheme used on the page using [WebAIM](https://webaim.org/resources/contrastchecker/) to check the colour contrast. 
![screenshot of colour contrast check](/documentation/contrast%20checker.png)

- I have also used the chrome extension [Web Disability Simulator](https://chromewebstore.google.com/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) to also consider the visuals of the page and contrast between the content for users with visual impairments.
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
- GitHub - used as the code editor and save files
- Bootstrap version 5.3 - Code for the navigation bar, carousel, cards and form have been used and amended for use. CSS styling was also used and modified from Bootstrap using the documentation and some JavaScript has been applied to assist the functionality of the bootstrap code and CSS
- Google Fonts -  to implement the fonts used in the site
- Font Awesome - for icons and logos used in the site
- Chrome dev tools - To test and troubleshoot various features and also test responsiveness of the pages 
- [Pexels.com](https://www.pexels.com/) - To source the images used in the site
- [Befunky](https://www.befunky.com/dashboard/) - to resize and alter the images
- [Tinypng](https://tinypng.com/) - To compress images
- [Cloudconvert](https://cloudconvert.com/jpg-to-webp) - to convert images to different file types. 
- [freeconvert](https://www.freeconvert.com/) - to convert video to webm
- [Favicon.io](https://favicon.io/emoji-favicons/) - to create an emoji favicon
- [Amiresponsive](https://ui.dev/amiresponsive) - to show the website on a range of device screens
- [Invideo AI](https://invideo.io/) - to create a custom AI video

## 5. Deployment  

The website is deployed using GitHub Pages. To Deploy the site using GitHub Pages:

1. Login (or signup) to GitHub.
2. Go to the repository for this project - [Pawsome Strolls](https://github.com/Chandni-L5/pawsome-strolls)
2. Click the settings button.
3. Select pages in the left hand navigation menu.
4. From the source dropdown select 'Deploy from a branch' and in the branch dropdown select 'main' and press save.
5. The site has now been deployed.
6. When returning to the code page in the repository a Deployments section will appear in the right side column - this process may take a few minutes before the site goes live. The deployed sight can be accessed via this link.

## 6. Testing
Please refer to [testing.md](/documentation/testing.md) file for all the testing carried out.

## 7. Credits
### 7.1 Code Used
- [Bootstrap](https://getbootstrap.com/) - as referenced in this readme, Bootstrap has been used to implement a number of elements in the page. 
    - navigation bar
    - grid layout
    - cards 
    - carousel 

### 7.2 Content
- [Chatgpt](https://chatgpt.com/) - has been utilised to create some of the text throughout the website. 
- [mycolor.space](https://mycolor.space/) - referred to in 2.1
- [Google fonts](https://fonts.google.com/) - referred to in 2.2 
- [Favicon.io](https://favicon.io/emoji-favicons/) - to create an emoji favicon


### 7.3 Media
- [Font Awesome](https://fontawesome.com/) - referred to in 2.2
- [befunky.com](https://www.befunky.com/dashboard/) - referred to in 2.3 
- [pexels.com](https://www.pexels.com/) - referred to in 2.3
- [Tinypng](https://tinypng.com/) - referred to in 4.2
- [Cloudconvert](https://cloudconvert.com/jpg-to-webp) - to convert images to different file types. 
- [Invideo AI](https://invideo.io/) - to create a custom AI video

### 7.4 Documentation and testing
I have used the following sources to help guide and structure the documentation of this project.
- [The love running readme template](https://github.com/Code-Institute-Solutions/readme-template?tab=readme-ov-file) 
- [A markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables)
- [Kera Cudmore's readme template](https://github.com/kera-cudmore/readme-examples/blob/main/milestone1-readme.md) - shared on slack
- [Diffchecker](https://www.diffchecker.com/)
- [W3C](https://validator.w3.org/)
-[Autoprefixer](https://autoprefixer.github.io/)
- [Gyazo](https://gyazo.com/en) plugin- to create gifs to use in the testing documentation
- [WebAIM](https://webaim.org/resources/contrastchecker/) - referred to in 3.3
- [Web Disability Simulator](https://chromewebstore.google.com/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) - referred to in 3.3
- [Amiresponsive](https://ui.dev/amiresponsive) - to show the website on a range of device screens


### 7.5 Acknowledgments 
I would like to acknowledge the following people who have helped me along the way in completion of this project. 

- Vernell Clarke - Alumni student at code institute who contributed valuable time to help teach me how to use various dev tools and troubleshoot a number of issues on the site. Vernell also took time to test out the site on various browsers.
- Moritz Wach - my Code Institute Mentor who made himself available during the busy Christmas period to help advise me on my progress.
- Oisin at tutor support who assisted me with some troubleshooting. 
- Ivan Kimpl - who took time to help me with quick questions when I was unsure of how to target a specific class and who also took time to create a custom AI video for my project with a script I provided.
- Lizzy_4p and Naveed_5p - who took time to respond to my peer code review request on slack.
- Tom, Prashant and Suraj - family and friends who helped to test out the site on various devices.
- Benji - My dog who inspired me and kept me company throughout this project.