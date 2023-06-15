![Create Dreams logo](assets/images/logo4.png)

Create Dreams is a website for balloon decorations and party hire business. So that potential customers can view the decorations the business can create and the items they have available to hire.
---
![Mockups](documentation/mock-up.png)
---
# CONTENTS

* [GOAL](#Goal)
* [USER STORIES](#User)
* [FEATURES](#Features)
* [HOME PAGE](#Home)
* [GALLERY PAGE](#Gallery)
* [CONTACT PAGE](#Contact)
* [RESPONSE PAGE](#Response)
* [TECHNOLOGIES USED](#Technologies)
* [DESIGN](#Design)
* [WIREFRAME](#Wireframe)
* [TESTING](#Testing)
* [BUGS](#Bugs)
* [DEPLOYMENT](#Deployment)
* [CREDITS](#Credits)


---
# Goal

* To display completed projects.

* To be informative to visitors.

* To show the user of the type work the company does and
 make it easy for users to contact and make enquiries.

# User Storie

### As Visitor

* As a user I want to be able to navigate the site easily.

* As a user I want to be able to find some images of the pass project.

* As a user I want to be able to find contact information.

* As a user I want to be able to submit an enquiry.

* As a user I want to be able to find contact information.

### As Business Owner

* As a business owner I want potential customers to be able to navigate the site easily.

* As a business owner I want potential customers to be able to send us an enquiry.

* As a business owner I want to be able to display our work in a gallery.

---

# Features

## Navbar

  ####  Links

   * HOME - takes the user's Main page where users can find out information on the business.

   * Gallery - takes the users to a gallery of images of the business's recent work.
   
   * Contact Us - takes the users to the contact form page where a form can be filled out so they can contact the business.

   ### Navigation is responsive

   * On large screens the logo floats left and the navigation bar float to the right inline.

   ![Navbar](documentation/navbar.png)

   * On small screens the navigation bar float under the logo to the centre of the screen.

   ![navbar-small](documentation/navbar-small.jpeg)

## Footer

* The footer is fixed to the bottom of the page.
* It contains links to the company's Facebook, Instagram, Twitter and tiktok pages.
* The links change colour when hovering over them.
![Footer](documentation/footer-image.png)

# Home Page

 ## *Introduction to Company*

  * Welcomes Visitors to the site.
  * Brief introduction to Business.
  * Informs visitors of the products the business has to offer.
  * Invites visitors to view the gallery page.
  * A Background Image of a bunch of pastel balloons is displayed behind the text which complements the colour palette.  

  ![Home page image](documentation/homepage-image.png)


 # Gallery Page

  * Has a background colour.
  * Each image has a colour border.
  * Each image has a figcaption.
  * It has up-to-date images of recent work completed by the company.

  ![Gallery page image](documentation/gallerypage-image.png)


  # Contact page

   *Contact page includes a contact form*

   * It has an Input field for Name which is required to be filled out.
   * It has an Input field for Email address which is required to be filled out.
   * It has a message box to fill out to send enquiries.
   * it has a submit button that leads to a response page.

   *Contact page includes a Map*
   * Google Maps was used to generate map.
   * The Map indicates the area which the business supplies. 

   ![Contact page image](documentation/contactpage-image.png)
   
  # Response page

   * Visitors are directed to the response page after submitting the contact form.
   * It displays a thank you message and informs the user that they will be contacted soon.
   * It then directs the user to the Home page. 


   ---

   # Technologies Used
   - [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) 
   - [CSS](https://developer.mozilla.org/en-US/docs/Web/css)
   - [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) 
   - [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid)
   - [Balsamiq](https://balsamiq.com/)
   - [GitHub](https://github.com/) 
   - [Codeanywhere](https://codeanywhere.com/)
   - [Canva](https://www.canva.com/)
   - [Google maps](https://www.google.com/maps/)
   - [Font Awesome](https://fontawesome.com/)

---

# Design

## Logo

* Logo was created using Canva.
* The design was chosen as identifies the business.
* Colors that align with the business image. 
* Logo, when clicked, leads back to the home page.


## Color Palette

![color palette](documentation/colorpalette.png) 
 
 ## Fonts
 
 * Fuzzy bubbles were the main font used on the website as it works well with the font in the logo. 

 ![Fuzzy Bubbles font](documentation/fuzzy-bubbles.png)


 *  Sriracha was used on the navigation menu as it balanced well with the font used in the main body and logo.

 ![Sriracha font](documentation/sriracha.png)

---
# [Wireframes](documentation/create-dream.png)
* Wireframes were created in Balsamiq 
* It includes a desktop and a mobile wireframe.

---
# Testing

* I have tested the site  on Chrome, Safari and Firefox
* I have tested the site on different screen sizes to confirm it is responsive.
* I have tested all links to confirm they are functioning.
---
## Validator Testing
### [W3C](https://validator.w3.org/) was used for validation of Html
* [Home page html](documentation/w3cindex.html.png) 
* [Gallery page html](documentation/w3cgallery.html.png)
* [Contact page html](documentation/w3ccontact.html.png)
 * [Response page html](documentation/w3cresponse.html.png) 

 ### [Jigsaw](https://jigsaw.w3.org/css-validator/) was used for validation of CSS
---
## Lighthouse Testing

### DESKTOP
* [Home page](documentation/light-testing/lh-hp-desktop.png)
* [Gallery page](documentation/light-testing/lh-gp-desktop.png)
* [Contact page](documentation/light-testing/lh-cp-desktop.png)
* [Response page](documentation/light-testing/lh-rp-desktop.png)

### MOBILE

* [Home Page](documentation/light-testing/lh-hp-mobile.png)
* [Gallery Page](documentation/light-testing/lh-gp-mobile.png)
* [Contact Page](documentation/light-testing/lh-cp-mobile.png)
* [Response Page](documentation/light-testing/lh-rp-mobile.png)
---
# Manual Testing
| Feature | Expect | Action | Result |Tested |
|---|---|---|---|---|
| Header ||||
| Logo | When clicked return to home page. | Click the logo on the header | Return to the home page when clicked.| Pass|
| Navbar Home Button| When clicked return to the home page. | Click the Home button in the header |  Home page opened when clicked. | Pass |
| Navbar Gallery Button| When clicked opens the gallery page. | Click gallery button in header | Gallery page opened | Pass |
| Navbar Contact Button | When clicked open contact page. | Click the contact button in the header | Contact page opened when clicked.| Pass |
| Form ||||
| Form Submit Button | When clicked contact form is submitted and a response page is opened.  | Click Submit Button|Contact form is submitted. | Pass |
| Form name input | Name Required | Enter Name | Name required to be able to submit form .| Pass |
| Form Email input| Email Required | Enter Email address | Email address required to be able to submit the form. | Pass |
| Response Page| Displays, after submit button, is clicked and redirects to the home page after 10 seconds | Click Submit button | Returns to home page when after 10 seconds.| Pass |
| Social media Icons | When clicked open the connecting website in a new tab. | Click the icon in the footer | opened a new tab to the relevant site. | Pass |


# Bugs

* There is an Error still showing but this error is due to Google map used on the contact page, I have tested it on multiple devices and everything work as it should. 

## Mistakes
* During the initial stages of the project I didnt commit or have clear commit messages as the project progressed I made improvements to this. 


# Deployment

* GitHub pages were used to deploy the site.
* This was done by: 
  1. Sign in to the GitHub account
  2. Go to [GitHub repository](https://edelcorbett.github.io/CREATE-DREAMS/),
  3. Go to the **Settings** 
  4. Click **Pages** on the navigation on the left-hand side.
  5. In the source section select the **Main** Branch
  6. Select the root folder
  6. Then click "Save".
* The site is deployed and is accessible by the URL at the top of the page

LIVE LINK  [CREATE DREAMS](https://edelcorbett.github.io/CREATE-DREAMS/)

# Future Features

As this is a new business I would like to implement these features as the business grows. 
* A booking system for the party hire equipment.
* An option to buy and make payments from the site.

# Credits 

* [CSS TRICKS](https://css-tricks.com/)
* Kevin Powell youtube channel for css tutorials.
* [Coolors](https://coolors.co/) was used to create the color palette.
* [Canva](https://www.canva.com/) was used to create logo.
* [Pexels](https://www.pexels.com/) was used for background image.
* [Flexbox forggy](https://flexboxfroggy.com/) to learn flexbox.
* [Stack overflow](https://stackoverflow.com/) for information.
* [W3Schools](https://www.w3schools.com/) was used as reference
* [Techsini](http://techsini.com/) was used for resposive mock-up.           
* [Font Awesome](https://fontawesome.com/) was used to create social media icons.
* [Slack Community](https://app.slack.com/) I use slack channels for guidance




## Images
* Background image was used from Pexels.
* All Images in the gallery were provided by Create Dreams.

## Acknowledgements
I would like to acknowledge 
* [Code Institute](https://codeinstitute.net/)
* [Slack Community](https://app.slack.com/) 
* Juliia Konn My Mentor for her advice and support thought out the project. 



