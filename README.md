# The Dead Swan

![Welcome to The Dead Swan](/documentation/multi-device-mockup.png) 


The Dead Swan was created as my first milestone project for the Code Institutes Level 5 Diploma in Web Application Development.

Link to deployed site: 



## CONTENTS

* [User Experience](#user-experience)
  * [Project Goals](#project-goals)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [Elements Found on Each Page](#elements-found-on-each-page)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Databases Used](#databases-used)
  * [Frameworks Used](#frameworks-used)
  * [Libraries & Packages Used](#libraries--packages-used)
  * [Programs Used](#programs-used)
    * [Google Books API](#google-books-api)
    * [Flask Blueprints](#flask-blueprints)
    * [Flask Migrate](#flask-migrate)
    * [Error Handling](#error-handling)
    * [Defensive Programming](#defensive-programming)
    * [Database Migration to ElephantSQL](#database-migration-to-elephantsql)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)
  
* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)

- - -

## User Experience

### Project Goals


### User Stories

#### __Target Audience__



#### __First Time Visitor Goals__

As a first time user of the site I want to be able to:

* 

#### __Returning Visitor Goals__

As a returning registered user of the site I want to be able to:

* 


#### __Admin User__

As an administrator for the site I want to be able to:

* 
- - -

## Design

### Colour Scheme

![Colour Scheme for The Dead Swan](/documentation/color-palette.png)

### Typography

I used Google Fonts to import the following fonts for use in the site:

##### Logo & Headings 

[Bokor](https://fonts.google.com/specimen/Bokor)

![Sample](/documentation/bokor.png)

##### Paragraphs 

[Inter](https://fonts.google.com/specimen/Inter)

![Sample](/documentation/inter.png)

##### Icons 

[Font Awesome](https://fontawesome.com/icons)

### Imagery

Favicon generated using [favicon.io](https://favicon.io/) ![Favicon](/assets/images/apple-touch-icon.png)

### Wireframes

Wireframes were created for mobile and desktop using Balsamiq.

#### __Home Page__

![Home Page](/documentation/wireframe-home.png)

#### __Menu Page__

![Menu Page](/documentation/wireframe-menu.png)

#### __Gallery Page__

![Gallery Page](/documentation/wireframe-gallery.png)

#### __Booking Page__

![Booking Page](/documentation/wireframe-booking.png)

#### __Booking Request Received Page__

![Booking Request Received Page](/documentation/wireframe-booking-request-received.png)




## Features

The website is comprised of 5 pages:

* Home Page
* Menu Page
* Gallery Page
* Booking Page
* Booking Request Received Page


### Elements found on each page


* Navbar -

  __Navbar__
  
* Bootstrap navbar styled to have right sided margin.
  
  ![Navbar](/documentation/manual-testing/homepage-nav.png)


  __Footer__

* Footer containing contact information, social media links and opening times for the business is displayed on all pages of the website. 

  ![Footer](/documentation/manual-testing/homepage-footer.png)

- - -

### Home Page

![Home Page](/documentation/manual-testing/desktop-index.png)

![Home Page](/documentation/manual-testing/mobile-index.png)

![Home Page](/documentation/manual-testing/tablet-index.png)

### History Page

![Menu Page](/documentation/manual-testing/desktop-history.png)

### Gallery Page

![Gallery Page](/documentation/manual-testing/desktop-gallery.png)

### Booking Page

![Booking Page](/documentation/manual-testing/desktop-live.png)

### Booking Request Received Page

![Contact Form Modal](/documentation/manual-testing/desktop-modal.png)

- - -

### Future Implementations

In future implementations I would like to:

* 

### Accessibility

I have been mindful during coding to ensure that the website is as accessible friendly as possible. This has been achieved by:

* Using semantic HTML.
* Using descriptive alt attributes and titles for images on the site.
* Providing information for screen readers where there are icons used and no text.
* Adding "current" to navigation for screen reader to inform of page being accessed.
* Ensuring that there is a sufficient colour contrast throughout the site.

- - -

## Technologies Used

### Languages Used

HTML, CSS.

### Databases Used


### Frameworks Used

[Bootstrap]()

### Libraries & Packages Used

[W3 Schools html](https://www.w3schools.com/html/default.asp)
[W3 Schools css](https://www.w3schools.com/css/default.asp)

### Programs Used

[Balsamiq](https://balsamiq.com/) - Used to create wireframes.

[Github](https://github.com/) - To save and store the files for the website.

[Google Fonts](https://fonts.google.com/) - To import the fonts used on the website.

[Font Awesome](https://fontawesome.com/)  - For the icons on the website.

[Google Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) - To troubleshoot and test features, solve issues with responsiveness and styling.

[Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.

- - - 

## Deployment & Local Development

### Deployment

The project was developed using Codeanywhere cloud IDE and pushed to GitHub using the inbuilt command line. To deploy to GitHub Pages from the [Github repository](https://github.com/al-ell/al-ell.github.io/tree/main) follow these steps:

    1. Log in to [GitHub]()
    2. Go to the [repository page](https://github.com/al-ell/al-ell.github.io/tree/main)
    3. Change the name of the respository to "username.github.io" : al-ell.github.io
    4. From the menu above the repository menu select __settings__
    5. On the left select __pages__ 
    6. Under __source__ select __deploy from a branch__
    7. Go to "username.github.io" : al-ell.github.io



### Local Development

#### How to Fork

    1. On GitHub.com, navigate to the octocat/Spoon-Knife repository
    2. In the top-right corner of the page, click __Fork__
    3. Under "Owner," select the dropdown menu and click an owner for the forked repository
    4. By default, forks are named the same as their upstream repositories. Optionally, to further distinguish your fork, in the "Repository name" field, type a name
    5. Optionally, in the "Description" field, type a description of your fork
    6. Optionally, select __Copy the DEFAULT branch only__
    7. Click __Create fork__   

#### How to Clone

    1. On GitHub.com, navigate to the main page of the repository
    2. Above the list of files, click __<> Code__
    3. Copy the URL for the repository
        * To clone the repository using HTTPS, under "HTTPS", click __clipboard icon__
        * To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click SSH, then click __clipboard icon__
        * To clone a repository using GitHub CLI, click GitHub CLI, then click __copy icon__
    4. Open Terminal, change the current working directory to the location where you want the cloned directory
    5. Type 'git clone', and then paste the URL copied earlier
    6. Press __Enter__ to create your local clone

- - -

## Testing

Please see [TESTING.md](TESTING.md) for all testing performed
- - -

## Credits

### Code Used


All instances of Tutor support and fixes found online are documented as comments in the code.

##### Gallery Page

[Responsive Gallery Tutorial](https://blog.logrocket.com/responsive-image-gallery-css-flexbox/)
[Responsive Gallery Source Code](https://codesandbox.io/s/delicate-wave-sts6l7?file=/index.html:313-2227)
To create the gallery page I followed the above tutorial to make the responsive gallery page. Doing this helped me to learn more about how flexbox works. After this I went to make the history page.

##### History Page

[Youtube Flexbox Tutorial](https://www.youtube.com/watch?v=Y8zMYaD1bz0)
I used the tutorial playlist above to make a flexbox grid layout that becomes a stack for a smaller resolution.

##### Live Page

[Youtube timeline tutorial](https://www.youtube.com/watch?v=TcYSRI1JFQE&t=6s)
I used the timeline and knowlege gained during the Resume project to make the timeline for the tour dates. 


##### Bootstrap Components  

* Bootstrap Grid and flexbox used across all pages

* Alert
* Buttons
* Navbar
* Modal
* Form

### Content

Content for this project was written by Gwilym Llywelyn.

### Media

* Homepage Image for larger screen resolutions [street-homeimage](https://www.pexels.com/photo/two-men-and-woman-sitting-next-to-each-other-2479312/)

* Homepage Image for smaller screen resolutions/Image for gallery [street2](https://www.pexels.com/photo/man-playing-guitar-beside-woman-and-man-listening-to-him-2479320/)

* Image for gallery [street3](https://www.pexels.com/photo/man-playing-guitar-on-street-2479323/)

* Image for gallery [trumpet](https://www.pexels.com/photo/people-performing-on-stage-442540/)

* Image for gallery [guitar](https://www.pexels.com/photo/two-men-and-woman-sitting-next-to-each-other-2479312/)

* Image for gallery [outdoor-concert](https://www.pexels.com/photo/man-playing-a-saxophone-16803242/)

* Image for gallery [outdoor-concert2](https://www.pexels.com/photo/    man-and-woman-dancing-while-man-in-black-clothes-playing-the-saxophone-on-the-roof-top-7502577/)

* Image for gallery [drums-studio](https://www.pexels.com/photo/man-in-black-jacket-playing-drum-5650907/)

* Image for gallery [garden-stage](https://www.pexels.com/photo/a-band-playing-music-in-a-park-in-summer-16803238/)

* Image for gallery [closeup-guitar](https://www.pexels.com/photo/close-up-of-a-man-playing-an-electric-guitar-8133318/)

* Image for history [history1](https://www.pexels.com/search/stage%20and%20tables/)

* Image for history [history2](https://www.pexels.com/photo/16844655/)

* Image for history [band-practice](https://www.pexels.com/photo/16844655/)

* Image for history [festival-stage](https://www.pexels.com/search/festival%20stage/)

* Video for history [youtube-video](https://youtu.be/wPRwhu7WKp4)

* Video for live [youtube-video](https://www.youtube.com/watch?v=St7G1F4mu_4&t=3s)

* Device mark up creator [markup maker](https://techsini.com/multi-mockup/index.php)