# Foodie Blog

## Purpose of the project

 Foodie is a food blog or website. The project has been build using html and CSS. This is a personal blog and the owner wants to share her experiences or experts in food with others. Through this website the owner shares her personal food recipes and want the visitors of the website to know about them and contact her regrading food recipe questions or suggestions through contact me page. 
 
Visit the live [website].
  ![ responsive Design Layouts]

## Table of Contents
  * [Purpose of the project](#purpose-of-the-project)
  * [User Stories](#user-stories)
  * [Features](#features)
  * [Future Features](#future-features)
  * [Typography and color scheme](#typography-and-color-scheme)
  * [Wireframes](#wireframes)
  * [Technology](#technology)
  *  [Testing](#testing)
      * [Validator Testing](#validator-testing)
      * [Accessibility Testing ](#accessibility-testing )
      * [Manual Testing](#manual-testing)
      * [Supported Screens and Browsers](supported-screens-and-browsers)
      * [Fixed Bugs](#fixed-bugs)
  *  [Deployment](#deployment)
  *  [Credits](#credits)
      * [Images](#images)
      * [Contents](#contents)
      * [Code](#code)


-----


## User Stories
- As a visiting user, I would like to know more about the owner of this blog/website.
- As a visiting user, I would like to contact the owner for business enquiries
- As visiting user, I would like to view more recipes by the owner
- As a visiting user, I would like to view recipes instructions in a separate page.
- As a visiting user, I would like to view all recipes within one page.
- As a visiting user, I would like to have a confirmation message after submitting the queries form in the contact me page.
- As a visiting user, I would like to find the social media accounts of this website/blog.
- As a visiting user, I would like to open social media links in to another tab.


## Features

### All pages - Header and Footer sections:
  All pages have a header and footer. 

  * **Header** - The header contains the logo in the left side and a side navbar in the right side.This is located at the top of every page. 
       
       ![Header](/assets/readme-images/header.PNG)
    
 
     * **Logo** - The logo has the home page hyperlink that returns the user to the home page. The logo has been created in an online software. 

     * **Nav Bar** - The nav bar has the links to the different sections of home page and pages of the website.


  * **Footer** - The footer exists on all pages. The footer consists of social media links at the center of it.
      ![footer](/assets/readme-images/footer-section.PNG)
  
  ### Home page (index.html):

   Including the header and footer, the home page also contains the hero image with welcome text, About me section & Favourite recipe section. 

  * **Hero image** this is the a landing section of home page. It has a simple text with a hero image.
      ![Hero section](/assets/readme-images/ladning-section.PNG)


  * **About me section** This section comes after hero image. This section shows the image of the owner of this blog and gives a detail information about her, by using 1st person.  
     ![About-me-section](/assets/readme-images/about-section.PNG)


  * **My favourite Recipes section** This section has three chosen or favourite recipes of the owner. Each recipe has a container with short information about the food and has a button. By clicking this 'read more' button, the user will be directed to the recipe isntructions' section which is located in to 'recipes' page. 

      ![favourite-recipes-section](/assets/readme-images/fav-recipe-section.PNG)  
 
    
  ### Recipes page (recipes.html):

   - Apart from header and footer this page has three sections that contains the instrcutions of each recipe from home page. 
   - The design and HTML strcuture is the same for all the three sections apart from contents. 
   - Each section has two parts, ingrdients and instructions of how to make the food. 

      <details> <summary>Recipes page Image</summary>

      ![first-section](/assets/readme-images/ramen-section.PNG)  
      ![second-section](/assets/readme-images/oats-section.PNG)
      ![third-section](/assets/readme-images/poke.PNG)

      </details>

### Contact-me page (contact-me.html):

  Including (header and footer) this page has a container which has two parts.
   1. Form part/
        The user can send their inquires, suggestions or comments to the owner of this blog.
   2. Message to the user
        By reading this text the user will understand the objective of this form. This will help the user to fill out the form effectivetly. 

      ![contact](/assets/readme-images/contact-section.PNG)

### Confirmation page (confirmation.html)
  - This page has simple thank you image in the right side and a recived message in the left side.
  - The user will be directed to this image after submmiting the contact me form. 
  - This page has been created so the user would know that their form details has been sent successfully.  
  - If the user tries to submit the form empty, it will give a message to fill the form fields. All the form fields should be filled to be able to submit it.

    ![confirmation-page](/assets/readme-images/thankyou.PNG)




## Future Feature

- Newsletter form
- Add more recipes section
- View recipe list
- View video tutorials for recipes
- View photo gallery


## Typography and color scheme
  ### Typography
  - The following google font was used for the website.
     - `'Roboto', sans-serif;`

  ### Color Scheme
  - The website uses the following colors that has also been used in the logo.
  - The colors were used in different types as hex and rgba.
  ![colors](/assets/testing/colors.PNG)

## Wireframes
  As these were the first prototype. There are some changes between them and the real website. For instance, images and some other slight changes that the developer changed while coding. 
  <details> <summary> Wireframes / prototypes </summary>

  ![home page](/assets/readme-images/wireframes/home-wireframe.png)
  ![recipes page](/assets/readme-images/wireframes/receipe-wireframe.png)
  ![contact page](/assets/readme-images/wireframes/contact-wireframe.png)
  ![confirmation page](/assets/readme-images/wireframes/confirmation-page.png)

  </details>


## Technology

  - HTML 
  - CSS

 ### Programs that were used:
  - Figma: create the prototype / wireframes.
  - Git
  - Github
  - Gitpod
  - Google Fonts
  - Font Awsome
  - Favicon
  - Am I responsive
  - ezgif.com: Changed jpg to webp



## Testing
*  ## Validator Testing
    The W3c validator was used to validated the each HTML page sepeartly. Also it was used to validate the style.css page.

 - **W3C Jigsaw CSS** 
    ![w3c css validation](/assets/testing/w3s-css-validation.PNG)

 - **W3C HTML Validation**

    - HTML validation of Home page 
      ![Home page validation result](/assets/testing/html-validatation-checked.PNG)

    - HTML validation of Recipes page 
      ![recipes-page-validation-result](/assets/testing/w3s-recipes-html-validation.PNG)

    - HTML validation of Contact-me page
      ![contact page validation result](/assets/testing/w3s-contact-me-html-validation.PNG)

    - HTML validation of Confirmation page
      ![confirmation page validation result](/assets/testing/w3s-confirmation-html-validation.PNG)



 *  ## Accessibility Testing 
      To analyze the performance, bes practice, accessibility annd SEO for the each page in the website the lighthouse within dev tools was used. 

    - **Home page**
      - Desktop [Full Report](/assets/testing/docs-lighthouse-reports/home-lighthouse-report-desktop.pdf)
        ![Home page results](/assets/testing/home-page-Desktop-result.PNG)
      
      - Mobile [Full Report](/assets/testing/docs-lighthouse-reports/home-lighthouse-reports-mobile.pdf)
        - Most of the performance marks were cut due to 'Eliminate render-blocking resources' warning. As for this project compressing css file has not been recommneded. Therefore, I did not change the css file.

         ![results](/assets/testing/homepage-lighthouse-result-mobile.PNG)


    - **Recipes page**
      - Desktop [Full Report](/assets/testing/docs-lighthouse-reports/recipes-lighthouse-reports-Desktop.pdf)
        ![Desktop-result](/assets/testing/recipes-results-desktop-lighthouse.PNG)
      
      
      - Mobile [Full Report](/assets/testing/docs-lighthouse-reports/Recipes-LightHouse-Report-Mobile.pdf)
        ![results](/assets/testing/Recipes-LightHouse-result-Mobile.PNG)


    - **Contact me page**
      - Desktop [Full Report](/assets/testing/docs-lighthouse-reports/Contact-me-Lighthouse-report-Desktop.pdf)
        ![Contact me desktop result](/assets/testing/Contact-lighthouse-result-Desktop.PNG)

      - Mobile [Full Report](/assets/testing/docs-lighthouse-reports/Contact-Lighthouse-Report-Mobile.pdf)
        ![Contact me mobile result](/assets/testing/Contact-lighthouse-result-Mobile.PNG)


    - **Confirmation page**
      - Desktop [Full Report](/assets/testing/docs-lighthouse-reports/Confirmation-Page-Lighthouse-Report.pdf)
        ![Confirmation desktop result](/assets/testing/confirmation-lighthouse-result-desktop.PNG)


  ## Manual Testing
  - This site was manually checked after uploading each feature. The features were interactive and worked successfully. 

  ## Supported Screens and Browsers
  - This website can work properly on Chrome, Firefox, Safari. 


  ## fixed bugs

   - The website wasn't loading style.css page and was giving an error. The error was about favicon(this little icon that shows in the browser tab). To fix it, favicon was added in the header.

   - W3S HTML validator found no error in the home page, but a warning,  "Section lacks heading" in all the sections of the page. Two approaches were taken to solve this issue
       1. remove section tag
       2. add h2 or h1 inside section tag

   - W3S CSS validator found parse error and in the Text-Area section. A semicolon was missing in a line of code. Therefore, by adding semicolon this issue was fixed. 

   - W3S HTML validator found another error, "Bad value for attribute srcset on element img: No width specified for image 'ramen' ". 
        - Fixed this issue by giving width to the image.

   - W3S CSS validator found another error "the value 'text' is deprecated". An unused line of code with no semicolon was found in the css file. By removing it this error was fixed. 

   - While checking the perofmance of the website in the lighthouse dev tools the following error occured:
        - Document does not have a meta description. Fixed this by adding meta description in the header of recipe page. 
    


## Deployment 
  This website was developed in Gitpod. It was deployed on github. 

  - The site was deployed to GitHub pages. The steps to deploy are as follows:
    - In the GitHub repository, navigate to the Settings tab
    - From the source section drop-down menu, select the Master Branch
    - Once the master branch has been selected, the page will be automatically    refreshed with a detailed ribbon display to indicate the successful deployment.

## Credits
  ### Images
  - [unsplash](https://unsplash.com/)
  - [pexels](https://www.pexels.com/)
  - Logo has been created within a free source software
  
  ### Contents
  - [Recipe website](https://www.forkknifeswoon.com/simple-homemade-chicken-ramen/)
  - [Read me deployment content](https://github.com/Code-Institute-Solutions/readme-template)
  
  ### Code
  - A part of footer's code was taken from [Love Running Code Project](https://learn.codeinstitute.net/ci_program/diplomainfullstacksoftwarecommoncurriculum).

