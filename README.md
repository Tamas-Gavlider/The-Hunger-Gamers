
# Hunger Gamers

Hunger Gamers is a responsive website allowing users to view on range of devices.<br> The purpose of the page is to get people together and  have a few carefree hours while playing video games and enjoying the delicious food. The weekend events will guarantee the fun for everyone.

![Responsivenes](/docs/testing/am-i-responsive.png)

[View Hunger Gamers on Github Pages](https://tamas-gavlider.github.io/The-Hunger-Gamers/)

## Contents
* [Web Page Goal](#web-page-goal)
* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Wireframe](#wireframe)
  * [Typography](#typography)
* [Features](#features)
  * [Home Page](#home-page)
  * [Menu Page](#menu-page)
  * [Events Page](#events-page)
  * [Registration page](#registration-page)
* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)
* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
* [Testing](#testing)
  * [Known Bugs](#known-bugs)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
    * [Index](#index-page)
    * [Menu](#menu-page-1)
    * [Events](#events-page-1)
    * [Registration](#registration-page-1)
  * [Wave](#wave)
  * [Full testing](#full-testing)
  * [Credits](#credits)
    * [Images](#images)
    * [Media](#media)
    * [Content](#content)
    * [Acknowledgments](#acknowledgments)

## Web Page Goal

* To be able to view the site on a range of device sizes.
* Create a community where gaming enthusiasts can come together.
* Provide details of the upcoming events.
* Offer delicious food.
* Connect people through social network platforms.

## Design

### Colour Scheme

The website uses black,red and yellow colours due to their strong visual impact <br>
and symbolic meanings:

* **Black:** Often associated with elegance, and modernity.
* **Red:** Conveys excitement, energy, and passion.
* **Yellow:** Represents happiness, optimism, and energy.
* **Gray** It was used as the background color on Events html due to contrast errors and background color<br>
on index html to overlap the background image.

These colours together create a bold, and energetic vibe.

### Wireframe 

Wireframes were created for mobile, tablet and desktop.

[Home Page for phone and tablet](/docs/wireframe/index-phones-tablet.png)<br>
[Home Page for desktop](/docs/wireframe/index-desktop.png)<br>
[Menu](/docs/wireframe/menu.png)<br>
[Events](/docs/wireframe/events.png)<br>
[Registration](/docs/wireframe/registration.png)

### Typography 

Google Font Silkscreen is being used for the website. The pixelated style used on 
webpage refers to classic video games, evoking nostalgia and retro feel.

## Features 

The website consists of four pages, three of which are accessible from the navigation menu (home page, menu page & events page).<br>
The fourth page is a confirmation page which is shown once a user submits the form on the events page.
* All pages on the website have:
  * Fully responsive [header](/docs/webpage_ss/header.png) with navigation links which allow the user to navigate through the site. The navigation links background color will change to yellow if the user hover over the navigation elements. The text Hunger Gamers is in the center of the page above the navigation links.<br>The navigation links to the websites pages (Home,Menu,Events) and the text Hunger Gamers will be visible on both cellphones and dekstops. This was implemented to keep the website design same/slightly different if user accessing the website on multiple devices. Less change in design will promote a good user experience.
  * A [footer](/docs/webpage_ss/footer.png) which contains social media links. The name of the social media platforms were used instead of the social media icons to keep the retro feeling with the pixelated fonts.
* #### Home page
  * With a [Nintendo NES](/docs/webpage_ss/index-page-top.png) console as background image.The first thing that user will notice is the console image and the text of "Speedruns & Game Marathons".
  * [Reasons](/docs/webpage_ss/index-page-reason-why-visit-us.png) why the user should visit the place.
  * [Introduction](/docs/webpage_ss/index-page-bottom-of-main.png) and contact email.
* #### Menu page
  * List of available dishes, drinks and snacks.<br>
  [Menu top](/docs/webpage_ss/menu-page-offers.png)<br>
  [Menu bottom](/docs/webpage_ss/menu-page-more-offers.png)
* #### Events page
  * The [upcoming events](/docs/webpage_ss/events-page-upcoming-events.png) with dates and details. User can click on the arrow to expand the event and check the details of it.<br>
  [Event details](/docs/webpage_ss/events-page-event-details.png)
  * [Registration form](/docs/webpage_ss/events-page-reg-form.png) with input fields and radio buttons.  
* #### Registration page
  * A [confirmation message](/docs/webpage_ss/registration-page.png) that the registration was successful.
   

## Technologies used

### Languages Used

HTML and CSS were used to create this website.

### Frameworks, Libraries & Programs Used 

Balsamiq - Used to create wireframes.

Git - for Version Control.

Github - To save and store the files for the website.

Google Fonts - To import the fonts used on the website.

Font Awesome - For the icon image.

Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and styling.

[Am I Responsive?](https://ui.dev/amiresponsive) - To show the website image on a range of devices.

[Cloudconvert](https://cloudconvert.com/jpg-to-webp) - To convert images to webp format.

[Favicon](https://favicon.io/favicon-converter/) - To create Favicon.

## Deployment & Local Development

### Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to Github.
1. Find the repository for this project, The-Hunger-Gamers.
1. Click on the Settings link.
1. Click on the Pages link in the left hand side navigation bar under "Code and Automation".
1. In the Source section, choose main from the drop down select branch menu. Select Root  from the drop down select folder menu.
1. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

**How to Fork**

To fork the The-Hunger-Gamers repository:

1. Log in (or sign up) to Github.
1. Go to the repository for this project, Tamas-Gavlider/The-Hunger-Gamers.
1. Click the Fork button in the top right corner.

**How to Clone**

To clone the The-Hunger-Gamers repository:

1. Log in (or sign up) to Github.
1. Go to the repository for this project, Tamas-Gavlider/The-Hunger-Gamers.
1. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
1. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
1. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

## Testing

I have used Chrome Developer tool while building the web page and troubleshoot any issues immediately. 

The following issues were raised during my mid project meeting with my mentor:

   * The background images were not converted to webp format. Due to the image size the Lighthouse gave low performance score.  
   * The source code contained too many unnecessary whitespaces.
   * Removing the method attribute from the Form element since the date will not be sent anywhere.
   * The mentor brought to my attention that the "Last Name" input is not required on the Events page. It is not required on purpose. User might have a long last name so skipping that field can save them time.
   * Collect elements into class which share the same attributes and reduce the duplicate codes in CSS.

  ### Known Bugs 

   The background image on index html should be fixed on mobile phones. It works fine in Chrome Developer Tool, and Android devices but not on Iphones. It was tested on Iphone 11 and Iphone 6.<br>This issue is due to lack of support for background-attachment in Safari on iOS devices.<br>
   This bug does not prevent the user to navigate through the web page.
   
  ### W3C Validator

   The W3C validator was used to validate the HTML on all pages of the website. It was also used to validate CSS in the style.css file. No errors were found, however there was a warning sign due to the imported google font.
  * [Index HTML](/docs/testing/validator/index-validator.png)<br>
  * [Menu HTML](/docs/testing/validator/menu-validator.png)<br>
  * [Events HTML](/docs/testing/validator/events-validator.png)<br>
  * [Registration HTML](/docs/testing/validator/registration-validator.png)<br>
  * [CSS](/docs/testing/validator/css-validator.png)<br>
  * [Warning sign](/docs/testing/validator/warning-sign.png)<br>

  ### Lighthouse

  I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

  #### Index page

  The performance was really low for mobile phones due to the google fonts.<br>
  I have tested the page without the google fonts, and the performance would have been 100.<br>
  Since the choosen font style is critical due to the theme of the web page, it will not be changed. 
  
  [Index page for desktop](/docs/testing/lighthouse/lighthouse-index-page-desktop.png)<br>
  [Index page for mobile](/docs/testing/lighthouse/ligthouse-index-page-mobile.png)<br>
  [Index page for mobile warning](/docs/testing/lighthouse/lighthouse-index-mobile-warning.png)<br>
  [Index page for mobile without google fonts](/docs/testing/lighthouse/lighthouse-index-page-with-google-fonts-removed.png)<br>

  #### Menu page

  [Menu page for desktop](/docs/testing/lighthouse/lighthouse-menu-page-desktop.png)<br>
  [Menu page for mobile](/docs/testing/lighthouse/lighthouse-menu-page-mobile.png)<br>

  #### Events page

  The performance was really low due to the google fonts, however at this time for desktop. The performance would have been 100 without the google fonts. I was able to improve the performance by changing the background color. 

  [Events page for desktop](/docs/testing/lighthouse//lighthouse-event-page-desktop.png)<br>
  [Events page for mobile](/docs/testing/lighthouse/lighthouse-events-page-mobile.png)<br>
  [Events page for desktop without google fonts](/docs/testing/lighthouse/lighthouse-events-page-desktop-google-fonts-removed.png)<br>
  [Events page for desktop with new BG color](/docs/testing/lighthouse/lighthouse-events-page-desktop.png)

  #### Registration page

  [Registration page for desktop](/docs/testing/lighthouse/lighthouse-registration-page-desktop.png)<br>
  [Registration page for mobile](/docs/testing/lighthouse/lighthouse-registration-page-mobile.png)

  ### Wave

  All the 4 pages were tested at [Wave](https://wave.webaim.org/).

  [Index page](/docs/testing/wave/wave-index.png)<br>
  [Menu page](/docs/testing/wave/wave-menu.png)<br>
  [Registration page](/docs/testing/wave/wave-registration.png)<br>
  [Events page](/docs/testing/wave/wave-events.png)<br>

  ### Full Testing

  I performed the following testing using a number of browsers (google chrome, safari, mozilla firefox,edge) and devices (Macbook Pro 15 inch, iMac 21.5 inch, iPhone 11, iPhone 6s and a 15 inch Dell laptop).<br>
  I also went through each page using google chrome developer tools to ensure that they responsive on all different screen sizes.<br>
  [Tested screens](/docs/testing/tested-screens.png)<br>
  Links:
  1. Test each link on the index page. Each link worked as expected, and any links leading to external pages opened correctly in a seperate browser tab.
  1. Test each link on the menu page. Each link worked as expected, and any links leading to external pages opened correctly in a seperate browser tab.
  1. Test each link on the events page. Each link worked as expected, and any links leading to external pages opened correctly in a seperate browser tab.
  1. Test each link on the registration page. Each link worked as expected, and any links leading to external pages opened correctly in a seperate browser tab.<br>

Registration form:
  1. The form worked as expected. Form could not be submitted without filling in the <em>First Name</em>,<em>Email</em> and choosing one of the radio buttons. If any of the field is not filled out/radio button not checked, the form directs the user to fill the empty field/select radio button.<br>
  [Test with required inputs](/docs/testing/reg-form-test/reg-form-test-no-details.png)<br>
  [Test with first name](/docs/testing/reg-form-test/reg-form-test-with-first-name.png)<br>
  [Test with first name and email](/docs/testing/reg-form-test/reg-form-test-with-fname-email.png)<br>
  [Test with radio button](/docs/testing/reg-form-test/reg-form-test-with-radio-button.png)<br>
  [Test with radio button and first name](/docs/testing/reg-form-test/reg-form-test-with-radiob-fname.png)<br>
  [Test with radio button and email](/docs/testing/reg-form-test/reg-form-test-with-email-radiob.png)

## Credits

### Images

All background images were downloaded from [Pexels.com](https://www.pexels.com).

### Media

All screenshots used in this README file were taken by myself.

### Content

  Content for the website was written by Tamas Gavlider. All the codes were written by Tamas Gavlider without using others' codes or tutorials. <br>
  I have only used the available resources from the Code Institue curriculum.<br>I have used the [Readme example](https://github.com/kera-cudmore/readme-examples?tab=readme-ov-file) to create this Readme.

### Acknowledgments

I would like to acknowledge:

* My Code Institute mentor Graeme Taylor for his valuable advices.










   