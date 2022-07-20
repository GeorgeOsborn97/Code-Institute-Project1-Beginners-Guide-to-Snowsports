# Your Snowsports Guide


"Your Snowsports Guide" was designed to provide valuable and useful infomation for people that are looking to get themselves, friends or family into the world of snowsports. specifically Skiing and Snowboading. Ideally any user will come to the end of the website with their questions answered, their doubts disuaded and a good base of knowledge that will help them on their journey into the world of snowsports.

Find a link to the deployed site [here:](https://georgeosborn97.github.io/Code-Institute-Project1-Beginners-Guide-to-Snowsports/)

## contents:
1. [User experiance](#user-experiance)
   - [Mockup desings](#simple-initial-design-plans)
2. [Features](#features)
   - [The background image and the general formatting](#the-background-image-and-the-general-formatting)
   - [Navigation bar](#navigation-bar)
   - [Information formatting](#neatly-formatted-information)
   - [Video/map](#videomap)
   - [Social links](#social-links)
   - [Brand links](#brand-links)
   - [User form](#ask-us-form)
3. [Technology that was utilised](#technology-that-was-utilised)   
   - [Languages](#languages)
   - [External assets](#external-assets-utilised)
4. [Testing](#testing)  
   - [HTML W3C Validation](#html-w3c-validation)
   - [CSS Jigsaw validation](#jigsaw-validation)
   - [Lighthouse](#lighthouse)
   - [Desktop results](#desktop-results)
   - [Mobile results](#mobile-results)
   - [Manual testing](#manual-testing)
   - [Device testing](#device-testing)
   - [user feedback](#user-feedback)
___
## User experiance:
### What I wanted to achieve:

1. Each user should come away from the website having learned something new about the world of snowsports.

2. If the user has a specific question that is not answered they will have the ability to ask their question.

3. The information provided is formatted in a clear and consistant way.

4. The website provokes a positive response through its imagary and formatting

5. The style of the website is consistant throughout all pages.

6. Responsive design allows the site to be easily viewed across multiple devices.
___
### Simple initial design plans:
Page | Mockup example |
--- | --- |
Index | ![desktop mockup of Home page](assets/mockup-images/page1-mockup.png) |
Getting started | ![desktop mock up of page 2 "getting strated"](assets/mockup-images/page2-mockup.png) |
What to buy? | ![desktop mock up of page 3 "What to buy?"](assets/mockup-images/page3-mockup.png) |
Ask us | ![desktop mock up of page 4 "Ask us"](assets/mockup-images/page4-mockup.png) |
Mobile example | ![mobile mock up of the home page and page 4 "Ask us"](assets/mockup-images/mobile-mockup.png) |
___
## Features: 
### The background image and the general formatting:
   - the background image aims to provides a feeling of warmth and joy due to the striking bright sun that captures the users initial attention.
   - the image aims to stand out and without distracting from the purpose of the site, its content. The fieldset provides enough difference to draw you to it without conflicting with the image.
   - the navigation elements at the top of the page are clear yet do not distract from the main text
![what the user first sees](assets/readme-images/opening-main-img.png)   
### Navigation bar: 
   - The simple clapsable navigation Icon provides the user a simple and effective way to navigate to the different pages of the site.
   - The styling is consistant throughout all pages and shows clearly which page the user is currently in as well as the repsonisve colour change that clearly highlights user interaction.
   - The main header/logo of the page is also a clickable link as is common place in many websites across the web.
![shut navigation bar image](assets/readme-images/shut-navbar.png)
![open navigation bar image](assets/readme-images/open-navbar.png)
### Neatly formatted information:
   - To avoid large portions of text that may confuse the user, all key information is contained within clapsable elements.
   - the clapsable elements clearly register interaction with a clear colour change and slight size shift. Enough to be visible but not ditracting.
   - With the large blocks of text hidden the user will be able to more easily find the specific information they seek.
![shut text block](assets/readme-images/clapsed-text.png)  
![open text block](assets/readme-images/open-text.png) 
### Video/map: 
   - The video in the index is completely user controlled they can choose to view it or not.
   - The aim of the video is to provide an additional more visual hook to the website that carries on the themes and goals of this site. Get more people into snowsports.
   - The map like the video provides are visual hook, however the purpose of this map is to give additional information regarding a specific topic in page 2.
![video on home page](assets/readme-images/video-image.png)  
![map on "getting started"](assets/readme-images/map-image.png) 
### Social links:
   - The social links at the bottom of every page simply allow the user to follow me on various social media platforms to see a more personal take on snowpsorts.
![social links](assets/readme-images/social-footer.png)   
### Brand links:
   - The brands links allow the user to go on to the various brands specific websites in a blank tab, in order to see for themselves what kind of equipment is out there and with the aid of this site make an informed decision on what they need.
![links to external brands](assets/readme-images/retail-links.png)   
### Ask us form:
   - The user form on the final page provides the user the ability to ask a more specfic question about any topic in the world of snowsports.
   - All areas must be filled in in order to post the form.
![user form](assets/readme-images/user-form.png)   
___
## Technology that was utilised:
### languages:
* HTML5
* CSS3
### external assets utilised:
* [GitHub](https://github.com/)
* [GitPod](https://gitpod.io/)
* [font awesome](https://fontawesome.com/)
* [google fonts](https://fonts.google.com/)
* [Uizard](https://uizard.io/)
* Chrome devtools
* Google images
* [W3C HTML validator](https://validator.w3.org/)
* [Jigsaw CSS validator](https://jigsaw.w3.org/css-validator/)
___
## testing:
### HTML W3C validation:
   - On the first test, the width was set incorrectly for both iframes in the index and page 2. this was fixed by removing the width="" atribute and using the style="" attribute for the width.
   - Also on the first test there was a highighted error in the iframes where i put a p element between the opening and closing tag. This had to be removed.
   - in the validation for the "Ask us" page a label error was highlighted, this was fixed by adding aria-labels to the submit and reset buttons.
   - on testing all pages there was a warning for sections with no headings, these were changed to divs to solve this.
   - On final validation no errors were highlighted in any of the HTML code.
### Jigsaw validation:
   - No errors were highlighted during CSS validation at any stage.
### Lighthouse:
#### Desktop results:
   - Index results
![index page desktop results](assets/readme-images/page1-desktop-results.png)
   - Getting started results
![getting started desktop results](assets/readme-images/page2-desktop-results.png)
   - What to Buy? results
![what to buy? desktop results](assets/readme-images/page3-desktop-results.png)
   - Ask us? results
![ask us? desktop results](assets/readme-images/page4-desktop-results.png)
#### Mobile results:
   - Index results
![index page mobile results](assets/readme-images/page1-mobile-results.png)
   - Getting started results
![getting started mobile results](assets/readme-images/page2-mobile-results.png)
   - What to Buy? results
![what to buy? mobile results](assets/readme-images/page3-mobile-results.png)
   - Ask us? results
![ask us? mobile results](assets/readme-images/page4-mobile-results.png)
### Manual Testing:
#### Device testing:
After the initial deployment these are the bugs that need addressing:
   1. Brand logos not showing on either desktop or mobile.
      - This bug was due to an error in the pathway to the images, with that clear the images loaded fine
   2. Icons for clapsable text are the default arrows on mobile
      - This issue appears to only be a problem for IOS, the icons load fine on Android. Issue still needs addressing on IOS
   3. On mobile the nav bar icon is now present when it should not be.
      - This issue is also only on IOS and still requires a fix.
   4. on mobile when the nav bar is selected a blue border is visible.
      - This is also an IOS issue that requires a fix.
   5. when the page is loaded on mobile the screen width is ok, however if you attempt to zoom out or scroll to the right, the image stops abrubtly and is a margin with the background colour is visible on the right.
      - This issue was due to the width of the h1 element, the width was set to 90vw and this appears to of solved this problem.
#### User feedback:
* 
*
*
___
## deployment:
All code was written in Gitpod, pushed to GitHub and deployed to GitHub Pages.

* In order to deploy our site from GitHub to Github pages the stages are as follows.
   - From the repostories page in GitHub select the project that needs to be deployed.
   - go to settings then on the right hand side menu select pages.
   - within this page go to the souce dropdown and select "main" then select save.
   - from here the link appears to our deployed site.   

## credits/acknowledgments
Content:
1. All code was written by myself no external code was utilised in this webpage. However stackoverflow was used regulary in order to gain a better understanding of how how certain elements interact and best practices for implementation.

2. Youtube video
3. google map
4. google fonts
5. font awsome

Media:
1. refrence where each image came from
