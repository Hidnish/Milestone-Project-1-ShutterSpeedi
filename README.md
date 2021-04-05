# **Shutter Speedi Photography** #

[View deployed site here](https://hidnish.github.io/Milestone-Project-1-/)

This is the official webpage of Shutter Speedi (Giacomo Spedicato), a London-based photographer. The site is simple, straightforward and offers any visitor the opportunity to explore the artist's professional background (in the **Home** page) and take a look at some of his best shots in the website's **Gallery** (accessible through the navbar).

For those interested in booking a photoshoot or simply contacting the photographer, the website offers a **Contact** section (also accessible through the navbar) which provides both the artist's contact details and a form, meant to facilitate the process, which can be filled in by the users to get in touch the photographer directly from the website. 

The business goals for the website:

* To build brand awareness 
* To boost the artist's image and credibility with a clean and professional self-hosted website.
* To provide examples of the artist's style of photography.
* Attract clients by facilitating user-provider communication in the contact section.

Customer goals for the website:

* To find a photographer to hire for high quality photoshoots. 
* To collaborate with the artist. 
* To be able to easily get in touch with the website's host.


## UX ##


* ### Target client ###

  * **The target client for this business is:**

     1. English speaking
     1. Most likely between 18 - 35 years old
     1. Lives in England

  * **Visitors would be searching for:**

     * A photographer to hire for a photoshoot or to collaborate with for a project.

   * **This website is the best way to help them achieve their goal for the following reasons:**

     1. It is simply structured and easy to navigate.
     1. Provides the client with easy steps to follow to absorb essential information.
     1. The amount of information provided is minimized to contain only the essential.
     1. Provides a path to fulfil the goal of the website: getting in touch with the artist.

* ### User stories ###

    * As a new visitor to the website:
      1. I want to easily navigate the site.
      1. I want learn about the artist and his credentials.
      1. I want view this artist's gallery to evaluate his skills.

    * As a potential client or interested observer:
      1. I want to know whether other clients have been satisfied with his work and the service received.
      1. I want to be able to easily get in touch with the artist.
      1. I want to follow the artist on social media and be updated about any news.

* ### Design ### 

  * **Colour Scheme**
    * The three main colors are: Aqua, Swamp Green and Gray.

  * **Typography**
    * The "Roboto Mono" font is the main font used throughout the whole website with "Sans Serif" as the fallback font. "Roboto Mono" has been selected as it fits with the retro style of the artist's photographs and the general look of the website. "Roboto" has also been used in the Quotes section in the Homepage.

  * **Imagery**
    * The Hero image in the home page was selected as it portraits the artist himself, is eye-catching and fits with the color scheme of the page. Same applies for the background image selected for the Contact page.

## Features ##


 * All Pages:
   * Responsive navbar with dropdown toggle for mobile screen sizes. The navbar contains: websites' logo (which brings user back to Home page when clicked) and links to Home, Gallery and Contact page.
   * Footer featuring 3 social media links/icons and copyright information.
   * All icons and navbar links change color when hovered over (except website logo and call to action arrow on the homepage hero image)

 * Homepage:
   * Fullscreen height hero-image with a Call to action icon (arrow) placed on the bottom linking to the artist's "About me" section.
   * "About me" section with info on the artist's background.
   * "Quotes" section showing quotes' from two of the artist's followers on social media.

* Gallery page:
   * Responsive gallery: with images displayed on 1 to 2 columns for mobile screen sizes and 2 to 3 columns for larger screen sizes.
   * A Fancybox slideshow: which activates by clinking on any of the pictures from the gallery and allows users to see the images in full, zoom, and slide through the gallery by clicking on the arrows placed on the right and left sides of the screen.

* Contact page:
   * Address, phone number and email address of the artist.
   * Contact form which requests client name, email and provides a text-area to be filled in with any specific request by the user. At the bottom of the form: a submit button.

## Technology Used ##


### Languages Used ###

* HTML5
* CSS3

### Frameworks, Libraries & Programs Used ###

1. [Bootstrap 4.6.0](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
   * Used to assist with the responsiveness and styling of the website.

2. [Google Fonts](https://fonts.google.com/)
   * Used to import the 'Roboto Mono' and 'Roboto' font into the style.css file which is used on all pages throughout the project.

3. [Font Awesome](https://fontawesome.com/)
   * Used on all pages throughout the website to add icons for aesthetic and UX purposes.

4. [Fancybox](https://cdnjs.com/libraries/fancybox)
   * Used for a gallery modal popup to slide through gallery images.

5. [jQuery]((https://getbootstrap.com/docs/4.6/getting-started/introduction/))
   * jQuery came with Bootstrap to make the navbar responsive. Also required for Fancybox gallery modal to function.

6. [Git](https://www.gitpod.io/)
   * Used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

7. [GitHub](https://github.com/)
   * Used to store the projects code pushed from Git.

8. [Balsamiq](https://balsamiq.com/)
   * Used to create the wireframes during the website's design process.

## Testing ##


* [W3C Markup Validator](https://validator.w3.org) / [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
  * Used to validate every page of the project to avoid syntax errors.

* Google Lighthouse 
  * Used to analyse and improve the website: performance, accessibility, best practices and SEO.

### Testing User Stories from User Experience (UX) Section ### 

 * As a new visitor to the website:
      * I want to easily navigate the website
        1. Every page is featured with a clean and easily readable navigation bar, with both: Home button and website logo linking to the homepage.
        2. Upon entering the site, the Hero image is featured with a Call to action arrow which helps the user to understand that more content is provided below the image.
      * I want learn about the artist and his credentials
        1.  Right below the Hero image, the "About me" section provides info regarding the artist's:
            * Background,
            * Photographic style and equipment,
            * Educational accreditations.
      * I want view this artist's gallery to evaluate his skills
        1. A clearly labelled Gallery page is provided in the navigation on every page.
        2. The artist's pictures are displayed in a simple and appealing way in the gallery, giving visitors the possibility of opening, zooming and sliding through different pictures.

 * As a potential client or interested observer:
      * I want to know whether other clients have been satisfied with his work and the service received
        1.  Quotes by some of the artist's followers on social media are displayed under the "About me" section, to further increase the photographer's trustworthiness.
      * I want to be able to easily get in touch with the artist
        1. A clearly labelled Contact page is provided in the navigation on every page.
        2. The contact page provides info such as the artist's: address, phone number and email.
        3. The contact page is also featured with a contact form, to get in touch with him directly from the website.
      * I want to follow the artist on social media and be updated about any news
        1. Three Social media icons are provided in the website footer on every page of the website.

### Further testing ###

* The Website was tested on Google Chrome, Safari, Opera, Firefox and Internet Explorer browsers.
* The Website was tested on a variety of screen sizes using Google Developer Tools and actual devices, such as: Desktop, Laptop, iPhone X, iPhone 8, iPhone 6s, iPad and Samsung Galaxy S III.
* Family and friends (including the photographer) were asked to test the website on their devices to detect any bug or UX issues.

### Bugs Solved ###

* The attribute "html, body {overflow-x: hidden;}" to allow the webiste to cover the entire viewport width for mobile screen sizes.
* Metadata "<meta name="format-detection" content="telephone=no">" was added to contact.html to remove default blue hyperlink color (creating visibility issues) from phone number when viewed on iPhone.

## Deployment ##


### GitHub Pages ####

* The project was deployed to GitHub Pages using the following steps:

  1. Log in to GitHub and locate the GitHub Repository
  2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu ("gear" icon).
  3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
  4. Under "Source", click the dropdown called "None" and select "Master Branch".
  5. The page will automatically refresh.
  6. Scroll back down through the "Settings" page to locate the now published site link in the "GitHub Pages" section.

* Forking the GitHub Repository

  By forking the GitHub Repository you make a copy of the original repository on your GitHub account to view and/or make changes without affecting the original repository. Forking requires the following steps:

  1. Log in to GitHub and locate the GitHub Repository
  2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
  3. You should now have a copy of the original repository in your GitHub account.

## Credits ##


### Code ###

* [Bootstrap 4](https://getbootstrap.com/docs/4.6/getting-started/introduction/): Used to structure the website with the "Grid system" and import JavaScript elements.
* [Fancybox](https://cdnjs.com/libraries/fancybox): JavaScript library used to create a slideshow in the website's gallery.
* [How to create Responsive LightBox Gallery with Bootstrap 4](https://www.youtube.com/watch?v=k-RtYiiB47E&ab_channel=webseotips): HTML code used to allow Fancybox gallery to function correctly.
* [Whiskey Drop - Code Institute](https://github.com/Code-Institute-Solutions/BootstrappingYourNextBigIdea-BS4/tree/master/04-BeyondBootstrap/03-cleaning_up_our_content): Used as a point of reference to build the website's Homepage. 
* [Resume Project - Code Institute](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/13-styling-personal-info-items): Used as a point of reference to build the Website's Contact page.
* [Stack Overflow](https://stackoverflow.com/): Used as source for HTML and CSS code used solve certain issues thoughout the project (credits provided beside each specific line of code).

### Content ###

* All content in the website was written by the Developer
* The README.md structure was based on:
  * [Code Institute Website's README.md ](https://github.com/Code-Institute-Solutions/SampleREADME)
  * [AJGreaves' README.md](https://github.com/AJGreaves/portrait-artist)

### Media ###

* All the pictures from the website were provided by [Giacomo Spedicato](https://www.facebook.com/giacomo.spedicato)

### Acknowledgement ###

* My mentor: Oluwafemi Medale, for his support and feedback