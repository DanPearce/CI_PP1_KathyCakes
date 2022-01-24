# KathyCakes - Bakery & Recipe Website
Developed by, Dan Pearce

[View the live site](https://danpearce.github.io/CI_PP1_KathyCakes/)

![Responsive](docs/responsive/responsive-index.png)
![Responsive-rtc](docs/responsive/responsive-rtc.png)

KathyCakes is a site that helps to encourage people to bake and create their own versions of the popular dishes from the KathyCakes Cafe. The website is intended to be a hub of information about the cafe and is here to help people get in touch with the cafe. The site offers a range of recipes too to help encourage people to try it at home themselves!

The site is designed with ease in mind and is easy to navigate for all ages. With use of high quality images to showcase the cafe and with the end goal purpose of attracting more sales. 

## Content
1. [Site Goals and Customer Experience](#site-goals-and-customer-experience)
    1. [Customer Goals](#customer-goals)
    2. [Website Owner Goals](#website-owner-goals)
    3. [Target Audience](#target-audience)
    4. [Customer Expectations](#customer-expectations)
2. [User Stories](#user-stories)
    1. [User](#user)
    2. [Website Owner](#webiste-owner)
3. [Design](#design)
    1. [Structure](#structure)
    2. [Wireframes](#wireframes)
    3. [Colour](#colour)
    4. [Fonts](#fonts)
    5. [Icons](#icons)
4. [Website Features](#website-features)
5. [Technologies](#technologies)
    1. [Languages](#languages)
    2. [Frameworks and Other](#frameworks-and-other)
6. [Validation and Testing](#validation-and-testing)
    1. [HTML Validation](#html-validation)
    2. [CSS Validation](#css-validation)
    3. [Accessibility Validation](#accessibility-validation)
    4. [User Story Testing](#user-story-testing)
    5. [Device and Browser Compatibility](#device-and-browser-compatibility)
7. [Bugs and Errors](#bugs-and-errors)
8. [Deployment](#deployment)
9. [Credits](#credits)
    1. [Images](#images)
    2. [Recipes](#recipes)
    3. [Code](#code)
10. [Acknowledgements](#acknowledgements)

## Site Goals & Customer Experience

### Customer Goals
- Easily find information about the bakery
- Easily find information on how to find the bakery.
- Get in touch with the bakery.

### Website Owner Goals
- Provide an alterative way to allow customers to get in touch.
- Provide a source of information about the bakery.
- Provide recipes for customers to try at home.
- Increase profits in store.
- Increase awareness about the bakery.

### Target Audience
- Regulars at the bakery.
- People who are looking to learn more about the bakery.
- People who are looking for new baking recipes.
- New customers who are looking to find the bakery.
- Customers looking to get in touch about an order/about placing an order.

### Customer Expectations
- Easy to navigate with a functioning navigational bar.
- Consistent design throughout, including design on all types of screen sizes.
- Fully functioning links, and no pages that lead to errors or dead links.
- Accessibility throughout the website.

## User Stories

### User
1. As a user, I want to easily find information about KathyCakes.
2. As a user, I want to easily navigate throughout the site.
3. As a user, I want to find information on how to find the bakery.
4. As a user, I want to find a way to get in contact with KathyCakes about an order.
5. As a user, I want to find a way to leave feedback to KathyCakes
6. As a user, I want to be able to find recipes that KathyCakes offers.
7. As a user, I want to find information about KathyCakes' social media.
8. As a user, I want to easily distinguish between different areas of information.

### Website Owner
9. As an owner, I want to showcase products on sale at the bakery.
10. As an owner, I want to provide customers with information about the bakery.
11. As an owner, I want customers to easily find our bakery.
12. As an owner, I want customers to be able to get in contact with us.
13. As an owner, I want to provide customers with the featured recipes of the season. 
14. As an owner, I want customers to be able to find all of our recipes easily.
15. As an owner, I want customers to find out about how we started.

## Design 

### Structure
I wanted the structure of the site to be easy to navigate with clear headings and sections to split the pages up while also staying consistent with design. The website has a total of 11 pages 4 of which you have access to at all times using the navigation bar, 6 which are recipe pages and a 404 page.

#### Nav Bar Pages
These pages are what I would consider to be the 'most popular' pages, they include key information about the bakery.
- 'KathyCakes' index.html to provide about us information and featured recipes.
- recipes.html to provide a place to find all recipes featured on the site.
- find.html to provide a page to give location information for the bakery.
- contact.html to provide a page for customers to get in touch with KathyCakes.

#### Recipe Pages, Individual
The 6 individual recipe pages are each unique and provide information that is specifically for each recipe. They all include a detailed image and instructions on how to make each peice.

#### 404 Page
This page has been implemented to provide a fall back in case of input error to ensure the user can remain on the site easily.

### Wireframes
<details><summary>Home Page</summary>
<img src="docs/wireframes/index.png">
</details>
<details><summary>Recipes Page</summary>
<img src="docs/wireframes/recipes.png">
</details>
<details><summary>Individual Recipe Page's</summary>
<img src="docs/wireframes/individual-recipes.png">
</details>
<details><summary>Find Us Page</summary>
<img src="docs/wireframes/find.png">
</details>
<details><summary>Contact Us Page</summary>
<img src="docs/wireframes/contact.png">
</details>


### Colour
The initial styling of colour comes from the header hero image of which the color #3c4044 can be found amongst the background in some variation. I thought this would be a great color to use as it's a charcoal grey which falls easily on the eyes. I also decided to go with #ecedf4 as the off white to counter balance this colour. These two colours are used throughout the site and stay consistent with the theme. 

I used [WEBAIM.org](https://webaim.org/) to test the contrast of the two colors. 
<img src="docs/validation/colour.png")


### Fonts
I have used three fonts in the creation of this website, [Meow Script](https://fonts.google.com/specimen/Meow+Script) for the Logo, as this gives a more unique feel. [Montserrat](https://fonts.google.com/specimen/Montserrat) for the navigational sections in uppercase as this to me felt like it stood out. Finally [Nunito](https://fonts.google.com/specimen/Nunito) was used for the main body sections as I felt this made the site easy to read and not too harsh on the eye.

### Icons
I used [favicon.io](https://favicon.io/) to create the favicon icons for the site with the [Meow Script](https://fonts.google.com/specimen/Meow+Script) font to stay consistent with styling. I also used icons from [Font Awesome](https://fontawesome.com/) to add the logos for social media networks in the footer.

## Website Features

### Navigation Bar & Footer
- The navigation and footer sections can be found on all pages. These are here for ease of access around the site and to showcase social media sections at all times.
- The nav bar is consistently placed at the top of the webpage for ease of access around the site. This is fixed into place no matter which page you visit!
![Nav-Bar](docs/features/feat-nav.png)
![Footer](docs/features/feat-foot.png)
User Stories Implementation: 2, 7, 8, 9

### Home About Us Section
- The Home/About Us Section is a key area to get information about the bakery.
- The section provides detail about how the bakery started, and also features a baked good at the top of the page.
- The section is intended to provide users with some background so they can get familiar with the KathyCakes.
![Home](docs/features/feat-index.png)
User Stories Implementation: 1, 10, 15

### Signature Recipes Section
- The Signature Recipes Section is here to highlight the bakery's featured recipes of the season.
- The section is featured on the index page and lets customers know which dishes we think they should try out!
![Signature](docs/features/feat-signature.png)
User Stories Implementation: 8, 9, 13

### Recipes Page
- The Recipes Page is the hub for all of the recipes that is offered on the site.
- The page styles according to screen size and offers users a range to choose from.
![Recipes](docs/features/feat-recipes.png)
User Stories Implementation: 6, 8, 9, 14

### Individual Recipe Page's
- The Individual Recipe Page's are all unique and there are six of them in total.
- The recipes are featured with their own unique hero image to really highlight the food on offer.
- These pages are designed with the user in mind to keep ingredients and instructions sectioned for ease of use.
![Recipes-Individual](docs/features/feat-recipes-indiv.png)
User Stories Implementation: 8

### Map
- The Map allows us to pinpoint where the bakery is right on a map which is featured on the users device.
- The Map is using the most popular online map in the world by Google and also features the address for more old school customers.
![Map](docs/features/feat-map.png)
User Stories Implementation: 3, 11

### Contact Form
- The Contact Form has been implemented as a way for customers to get in contact with KathyCakes with ease.
- The form can be used to enquire about orders or to leave feedback to the bakery. 
![Contact](docs/features/feat-form.png)
User Stories Implementation: 4, 5, 12

## Technologies

### Languages
- [HTML](https://en.wikipedia.org/wiki/HTML5)
- [CSS](https://en.wikipedia.org/wiki/CSS)

### Frameworks and Other
- [GitHub](https://github.com/)
- [GitPod](https://www.gitpod.io/)
- [Font Awesome](https://fontawesome.com/)
- [Balsamiq](https://balsamiq.com/)
- [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
- [Google Fonts](https://fonts.google.com/)
- [Favicon.io](https://favicon.io/)

## Validation and Testing

### HTML Validation
All of the HTML pages were tested using the [W3C Markup Validation Service] in order validate the correct function of this site. All pages have passed with no errors or warnings.

<details><summary>Home Page</summary>
<img src="docs/validation/index-validation.png">
</details>
<details><summary>Recipes Page</summary>
<img src="docs/validation/recipes-validation.png">
</details>
<details><summary>Apple & Cinnamon Crumble Cupcakes Page</summary>
<img src="docs/validation/accc-validation.png">
</details>
<details><summary>Banana & Pumpkin Seeded Muffins Page</summary>
<img src="docs/validation/bpsm-validation.png">
</details>
<details><summary>Chocolate Chip & Peanut Cookies Page</summary>
<img src="docs/validation/ccpc-validation.png">
</details>
<details><summary>Grandma's Signature Lemon Loaf Page</summary>
<img src="docs/validation/gsll-validation.png">
</details>
<details><summary>Pink Grapefruit Muffins Page</summary>
<img src="docs/validation/pgm-validation.png">
</details>
<details><summary>Raspberry Twist Cupcakes Page</summary>
<img src="docs/validation/rtc-validation.png">
</details>
<details><summary>Find Us Page</summary>
<img src="docs/validation/find-validation.png">
</details>
<details><summary>Contact Us Page</summary>
<img src="docs/validation/contact-validation.png">
</details>


### CSS Validation
The [W3C Jigsaw Validation Service](https://jigsaw.w3.org/css-validator/) was used to validate the correct CSS of this website. The CSS has passed with no errors
<details><summary>CSS</summary>
<img src="docs/validation/css-validation.png">
</details>

### Accessibility Validation
The [WAVE - Web Accessibility Evaluation Tool](https://wave.webaim.org/) was used to test the accesibility function of the website, all pages have passed with no errors.
<details><summary>Home Page</summary>
<img src="docs/validation/access-index.png">
</details>
<details><summary>Recipes Page</summary>
<img src="docs/validation/access-recipes.png">
</details>
<details><summary>Apple & Cinnamon Crumble Cupcakes Page</summary>
<img src="docs/validation/access-accc.png">
</details>
<details><summary>Banana & Pumpkin Seeded Muffins Page</summary>
<img src="docs/validation/access-bpsm.png">
</details>
<details><summary>Chocolate Chip & Peanut Cookies Page</summary>
<img src="docs/validation/access-ccpc.png">
</details>
<details><summary>Grandma's Signature Lemon Loaf Page</summary>
<img src="docs/validation/access-gsll.png">
</details>
<details><summary>Pink Grapefruit Muffins Page</summary>
<img src="docs/validation/access-pgm.png">
</details>
<details><summary>Raspberry Twist Cupcakes Page</summary>
<img src="docs/validation/access-rtc.png">
</details>
<details><summary>Find Us Page</summary>
<img src="docs/validation/access-find.png">
</details>
<details><summary>Contact Us Page</summary>
<img src="docs/validation/access-contact.png">
</details>

### User Story Testing
1. As a user, I want to easily find information about KathyCakes.
- Information about KathyCakes can easily be found right on the index.html page, either by scrolling down slightly depending on screen size or right on the landing page without movement.
<details><summary>User Story 1</summary>
<img src="docs/user-story-testing/user-testing-1-10-15.png">
</details>

2. As a user, I want to easily navigate throughout the site.
- The navigation bar is at the top of the website and is fixed into place, this is for ease of access on all web pages and all screen sizes.
<details><summary>User Story 2</summary>
<img src="docs/user-story-testing/user-testing-2.png">
</details>

3. As a user, I want to find information on how to find the bakery.
- The Find Us page is dedicated for users to find the bakery, this is located in the nav bar for easy access.
<details><summary>User Story 3</summary>
<img src="docs/user-story-testing/user-testing-3-11.png">
<img src="docs/user-story-testing/user-testing-map.png">
</details>

4. As a user, I want to find a way to get in contact with KathyCakes about an order.
- The Contact Us Page is dedicated for users to contact the bakery, located on the nav bar, this can be used for orders.
<details><summary>User Story 4</summary>
<img src="docs/user-story-testing/user-testing-4-5-12.png">
<img src="docs/user-story-testing/user-testing-form.png">
</details>

5. As a user, I want to find a way to leave feedback to KathyCakes
- The Contact Us Page is dedicated for users to contact the bakery, this can be used for customer feedback.
<details><summary>User Story 5</summary>
<img src="docs/user-story-testing/user-testing-4-5-12.png">
<img src="docs/user-story-testing/user-testing-form.png">
</details>

6. As a user, I want to be able to find recipes that KathyCakes offers.
- The Recipes page is located on the navigation bar and provides a home page for all recipes on the site.
<details><summary>User Story 6</summary>
<img src="docs/user-story-testing/user-testing-6-14.png">
<img src="docs/user-story-testing/user/testing/recipes.png">
</details>

7. As a user, I want to find information about KathyCakes' social media.
- Social Media links can be found in the footer of the website, this is on every page and uses icons of the logos of the social media sites for easily recognition.
<details><summary>User Story 7</summary>
<img src="docs/user-story-testing/user-testing-7.png">
</details>

8. As a user, I want to easily distinguish between different areas of information.
- Different information areas can be found in several places on the website, the most detailed is on the individual recipe pages which highlights and seperates the ingredients and instructions sections. 
<details><summary>User Story 8</summary>
<img src="docs/user-story-testing/user-testing-8.png">
</details>

9. As an owner, I want to showcase products on sale at the bakery.
- All of the images used are of products that are for sale in the bakery, this way highlighting them on all pages allows us to showcase them.
<details><summary>User Story 9</summary>
<img src="docs/user-story-testing/user-testing-9.png">
</details>

10. As an owner, I want to provide customers with information about the bakery.
- Information about the bakery can easily be found right on the index.html page, either by scrolling down slightly depending on screen size or right on the landing page without movement.
<details><summary>User Story 10</summary>
<img src="docs/user-story-testing/user-testing-1-10-15.png">
</details>

11. As an owner, I want customers to easily find our bakery.
- Information on where to find the bakery can easily be found by using the nav bar, and going to find us, this brings you to find.html which showcases a map, and also details the address.
<details><summary>User Story 11</summary>
<img src="docs/user-story-testing/user-testing-3-11.png">
<img src="docs/user-story-testing/user-testing-map.png">
</details>

12. As an owner, I want customers to be able to get in contact with us.
- The contact us page which can be found by using the nav bar, and clicking contact us provides a form for customers to get in contact with the bakery.
<details><summary>User Story 12</summary>
<img src="docs/user-story-testing/user-testing-4-5-12.png">
<img src="docs/user-story-testing/user-testing-form.png">
</details>

13. As an owner, I want to provide customers with the featured recipes of the season.
- Scrolling down the index.html page will bring you to the Signature Recipes section, where key highlighted recipes can be found. These are decided on the season, with Christmas being the latest theme! 
<details><summary>User Story 13</summary>
<img src="docs/user-story-testing/user-testing-13.png">
</details>

14. As an owner, I want customers to be able to find all of our recipes easily.
- The recipes page located on the nav bar is accessible at all times and when clicked brings you to the page where all of the recipes are located.
<details><summary>User Story 14</summary>
<img src="docs/user-story-testing/user-testing-6-14.png">
<img src="docs/user-story-testing/user/testing/recipes.png">
</details>

15. As an owner, I want customers to find out about how we started.
- On the index.html page, half way through the about us section we can find information about how KathyCakes started. This information is easy to access as is right on the home page of the website. 
<details><summary>User Story 15</summary>
<img src="docs/user-story-testing/user-testing-1-10-15.png">
</details>

