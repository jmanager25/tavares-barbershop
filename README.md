# Tavares Barbershop

Tavares Barbershop is a website created to provide potential clients with important information about services, opening hours, and location of the shop. It aims to boost the barbering bussiness, bring in clients and help the growt of the shop.

![Responsive Mockup](/assets/images/project-image.jpeg)

[View Tavares Barbershop website on github pages](https://jmanager25.github.io/tavares-barbershop/)

## Table of Contents

* [Design Section](#design-section)
   * [Colour Scheme](#colour-scheme)
   * [Typography](#typography)

* [Features](#features)
   * [Existing Features](#existing-features)
      * [Navigation Bar](#navigation-bar)
      * [Hero Image](#hero-image)
      * [About Us Section](#about-us-section)
      * [Service & Price Section](#service--price-section)
      * [Contact Section](#contact-section)
      * [Footer](#footer)
      * [Gallery Page](#gallery-page)
      * [Book Appointment Page](#book-appointment-page)

* [Technologies Used](#technologies-used)
   * [Languages Used](#languages-used)
   * [Framework, Libraries and Programs Used](#frameworks-libraries--programs-used)

* [Deployment](#deployment)

* [Testing](#testing)
   * [Manual Testing](#manual-testing)
   * [W3C Validator](#w3c-validator)
   * [Bugs](#bugs)

* [Credits](#credits)
   * [Code Used](#code-used)
   * [Content](#content)
   * [Media](#media)

* [Ackonowledgments](#acknowledgments)

## Design Section

### Colour Scheme

![Tavares Barbershop colour pallete](/assets/images/color-pallet.jpeg)

This colour pallete is from Barbershop Landing Page
by Dmitry Lauretsky 

### Typography

Google Fonts was used for the following fonts:

* Montserrat - for headings

* Roboto - for paragraphs

## Features

The website us comprised of three pages (home page, gallery page and book appointment page), all of them accssible from the navigation bar.

### Existing Features 

#### Navigation Bar

* Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, About Us, Services, Contact, Gallery page and Book Appointement page.
* On devices smaller than 980px the navigation bar turns into hamburger menu, allowing good user experience.

![navigation bar](/assets/images/navigationbar.jpeg)
![hamburger menu](/assets/images/hamburger-menu.jpeg)

#### Hero Image
 
* The landing page includes a photograph of barber products.

 ![landing page image](/assets/images/landing-page-image.jpeg)

#### About us section 

* This section includes the barbershop photograph and tell the users the story of the shop and its mission.
* This section also includes a link that leads the users to the book appointment page.

  ![about us section](/assets/images/About-us.jpeg)

#### Service & Price section  

* This section gives the users some information about the services provided by the barbershop and a brief description of each of the services.
* This section also shows the user the price of each of the services.

   ![services & price section](/assets/images/service-section.jpeg)

#### Contact section

* This section gives users information about address, phone number, email and opening times of the shop.
* This section includes an iframe of google maps that allows users to see exactly where the shop is located.

   ![contact section](/assets/images/contact.jpeg)

#### Footer

* The footer section includes links to the social media. Icons were used to keep the footer clean and because they are universally recognisable.

   ![footer](/assets/images/footer.jpeg)

#### Gallery page

* This section allows users to see the work done in the barbershop.
* This section gives users a visual representation of how their hair will look after the job is done.

   ![gallery page](/assets/images/gallery.jpeg)

#### Book appointment page

* This section allows user to make an online appointment with the barbershop.
* The user will be asked to submit their name, email and phone number, to select the service pretended, to choose the appointment date and time and to write any aditional message they find pertinent. 

   ![book appoitment page](/assets/images/form.jpeg)

## Technologies Used

### Languages Used

* HTML 

* CSS 

### Frameworks, Libraries & Programs Used

Git - For version control.

Github - To save and store the files for the website.

Google Fonts - To import the fonts used on the website.

Font Awesome - For the iconography on the website.

Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and styling.

[Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.

## Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

* Log in (or sign up) to Github.
* Find the repository for this project, tavares-barbershop
* Click on the Settings
* Click on the Pages, on the left side navigation bar
* Under "Branch" click the drop-down menu and select "main"
* click save, the site is now deployed and a link is provided.

## Testing

### Manual Testing

* All links on navigation bar opens to corect sections and pages.
* Social media links on footer opens on a new tab.
* All images on a website loads corectly.
* The form sends data correctly to the form dump.
* The website is fully responsible on all devices present on google dev tools

### W3C Validator

The W3C validator was used to validate the HTML on all pages of the website. It was also used to validate CSS in the style.css file.

* [Index Page HTML](assets/test/validation/index-page.jpeg)
* [Galery Page HTML](assets/test/validation/gallery-page.jpeg)
* [Book Appointment page](assets/test/validation/book-appointment-page.jpeg)
* [Style.css CSS](assets/test/validation/css-file.jpeg)

### Bugs

* On smaller screens the nav bar would wrap and come on top of the gallery and form page. In order to fix that issue, the flex wrap was removed and the hamburguer menu was added on devices smaller than 980px. 

![Before](/assets/test/bugs/navbar-bug.jpeg) 
![After](/assets/test/bugs/navbar-solution.jpeg)

* When using hamburguer menu on smaller screens the toggle menu would scroll with the page and disappear from the screen. To fix the issue the position fixed was added to the toggle menu.

![Before](/assets/test/bugs/toggle-menu-before.jpeg) 
![After](/assets/test/bugs/toggle-menu-after.jpeg)

* On bigger screens the footer would appear in the middle of the screen, in order to solve the problem, the media query was added to stick the the footer at the bottom of the page.

![Before](/assets/test/bugs/footer-before.jpeg) 
![After](/assets/test/bugs/footer-after.jpeg)

* In the Gallery page there were gaps between the images, because not all of them were the same size. This was solved by adding media query so that the images would adapt to the size of the screen. 

![Before](/assets/test/bugs/gallery-before.jpeg) 
![After](/assets/test/bugs/gallery-after.jpeg)

## Credits 

### Code Used

* [Code for hamburguer menu](https://www.youtube.com/watch?v=XM7sEpl0f7c&ab_channel=PureCode)

* [How to make footer stick at the bottom of web page](https://dev.to/nehalahmadkhan/how-to-make-footer-stick-to-bottom-of-web-page-3i14)

* [Fix the gap between the images on bigger screens](https://css-tricks.com/adaptive-photo-layout-with-flexbox/)

* Footer code was based on Love Running project

### Content

* The text for the about us section and services & price section were based on [Barbershop De Loods](https://barbershopdeloods.nl/) and [Barbershop Strak Strak](https://barbershopstrakstrak.nl/).

* The Icons in the footer are from [Font Awesome](https://fontawesome.com/)

* The readme file is based on Love Running readme and Kera Cudmore's webinar [Creating your first README](https://docs.google.com/presentation/d/19_7r_To5bu7UjnZD87hrzWQi63Ij0YpaRH1XFnPZZe8/edit#slide=id.g35f391192_04)

* Form dump from Code Institute

* Adress on contact section from kapsalon latino, a barbershop in rotterdam.

### Media 

* Images used on the website were taking from the foolowing website:

   * [Unsplash](https://unsplash.com/)
   * [Pxhere](https://pxhere.com/) 
   * [Pexels](https://www.pexels.com/pt-br/)

* Logo was created using canvas

* color pallets from [Dribbble](https://dribbble.com/shots/16129871-Barbershop-Landing-Page/attachments/7983429?mode=media)

## Acknowledgments

I would like to thank the following people:

* My girlfriend for her patiente and support while i was working on the project

* My mentor, Mitko, for his guidence throughout the project

* My collegues from code institute for the support and motivation on Slack







