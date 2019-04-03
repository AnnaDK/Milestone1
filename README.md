# Milestone project "The Monkees"

This project is a frontend-only website built by using the technologies that I've learned throughout User Centric Frontend Development. 
The project is a static website for a 60's band "The Monkees". 
The purpose of the project is to implement my knowledge by creating a 4-5 pages responsive website which represents guidelines given by Code Institute and requirements from interviews with the client’s representatives.

You can see my project here ["The Monkees"](https://annadk.github.io/Milestone1/) 

## UX
The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world.    
The main target auditory going to be old fans of the band.  Who is into the music and style of the '60s '70s. But the target is also to attract new fans by combining style and technology which fit for a wide range of auditory.
Navigation supposed to be easily understandable and content could be followed in an intuitive way.
In my research, I was monitoring social pages where you can find information about "The Monkees" , photos or their music and were reading comments from their fans. For me was an obvious high level of interest to any new information about the band. Also, people having an interest to see their new performances. 
This website gives an opportunity to contact the band in request of hiring them as well as following updates about concerts and receiving bands newsletters. 
As well as the possibility to listen to music, watch videos and enter more opportunities to stay in touch with the band and their fans, around the world,  by following social links.


### User Stories

* As a current fan, I would like to have information about concerts. Dates and locations
* As a person who loves music from the '60s 70's  I would love to see if the band is still performing. A big plus is the chance to make a booking for privet events.
* As a potential fan, I would like to read information about the band and band members.
* As a current fan would like to visit an application by following a link from the newsletter, to read fresh information and updates.
* As a visitor who didn't know the band before I would like to have some information, listen to their hits, watch videos.
* As a current fan would like to have on the web site actual social links.  It gives the opportunity to skip searching between a certain amount of different channels and pages.
* As a music fan, I always like to go through Band's discography, to listen to their Greatest Hits.
* As a potential fan, I like to watch Band's pictures, have a quick link for more information or other pages in social media. Where I can meet more fans.

### Mockups

[Large screen](Mockups/Mockup_The_Monkees.pdf)

[Mobile phones format](Mockups/Mockup_Mobile.pdf)

## Features

**In all pages**

* Background picture: Collage from albums covers and photos. Made online at [Pixlr.com](https://pixlr.com/express/).
* Navigation-bar: 
  
  Navigation element from bootstrap,  style updated with CSS. Collapsing on the small screen.

  Logo *guitar* for Navbar: adjusted online at [Pixlr.com](https://pixlr.com/express/)  Working as a link to the "Home" page if users click on it.
  
  Sign up button: opening a Modal window. By clicking on it, opens a separate window with a form.  The modal feature from bootstrap and the style updated in CSS. 
  
  Form for modal: From Bootstrap. Style updated with CSS. Allows users to subscribe for news and updates, by subscribing with e-mail. Submit button redirecting to "Thank you page".
  
  Navigation-items: Navigating users to the other pages of the web site, element from bootstrap. Style updated with CSS.

* Footer: 
  Social links: bringing users to social pages. Facebook, YouTube, Twitter.
  
  Icons: The FontAwesome icons from [fontawesome.com](https://fontawesome.com/start). Style updated with CSS.
   
  Sign up button: opening a Modal window. Users can subscribe for the news and updates, by filling in their e-mail.  The modal feature from bootstrap. Style updated with CSS.

**[index.html](index.html)**

* Side-content: Advertising for content from the website such as Tour dates and Booking form. With links to the "Contact page".
* Content-home: Articles  allows users to read about the band and separate about each band member by following a "Read more" link 
* to [Wikipedia](https://en.wikipedia.org/wiki/The_Monkees).

**[gallery.html](gallery.html)**

* photos: Allows users to see some band photos each one separate, by clicking on it. Download them on a users computer by clicking the "Download" button. The icon for download button, from fontawesome.com

**[music.html](music.html)**

* Discography: Allows users to see the name of albums and year of release.  Information is taken from Wikipedia
* Timeline: Made with the help of information from "Users centric development" module and [w3schools.com](https://www.w3schools.com/).
* Audio: Element audio with the controls allows users to listen/paused/change volume by clicking on it.
* Rotating elements: Albums covers. Styled with "rounded-circle" class in html. Animation style in CSS file. Rotating when hovering
* Video: Iframe responsive element from Bootstrap. Allows users to watch embedded video file from [Youtube.com](https://www.youtube.com/).

**[contact.html](contact.html)**

* Tour Dates: Allows users to see concert dates and places. Information from [monkees.com](https://www.monkees.com/).
   Table element for TOUR dates from Bootstrap. Style updated in CSS.
* Booking form: from Bootstrap. Style updated in CSS. Allows users to send a request by feeling email address, choosing a kind of event and feeling description field.
  Submit button redirecting to "Thank you page".

### Features Left to Implement
* Actual news page. Last band's news, interviews, plans, etc.
* Links to buy tickets online for concerts.
* News letters for users.

## Technologies Used

**[Balsamiq](https://balsamiq.com/)** to create the initial mockups for the website.

**HTML5**: used to construct a project.

**CSS3**: was used in order to add style.

**[Bootstrap 4](https://getbootstrap.com/)**: in order to use some of the components. The style sheet from Bootstrap is placed inside HTML.

**GIT**: to track changes in the website and push them to GitHub.

**[GITHUB](https://github.com/)**:to deploy the website and as the remote repository. 

**[Google](https://www.google.nl/)**:as main search engine. 

**[Cloud 9](https://ide.c9.io)**: as a development environment to write the code.

**[Pixlr.com](https://pixlr.com/express/)**:  to make Collage for background and remove the background from Logo for Navbar.

**[w3schools](https://www.w3schools.com/)**: as an extra information/help/knowlege sourse.

**[css-tricks](https://css-tricks.com/)**: as an extra information/help/knowlege sourse.

**[color-hex](https://www.color-hex.com/)**: to choice color palette.

**Javascript and JQuery**: are imported.

**Libraries:** 
**[Google fonts](https://fonts.google.com/)**. 
**[Font Awesome](https://fontawesome.com/start)**. 
 

## Testing

**Validation**

HTML: [validator.w3.org](https://validator.w3.org/) in order to validate the HTML code.
CSS: [jigsaw.w3.org]( https://jigsaw.w3.org/css-validator/) in order to validate the CSS code.

The website, all links, music tracks audio controls and video player were tested. 
Testing of the website was in Chrome developer tools, in all possible screen sizes, and different devices. On mobile phones: iPhone, Huawei, Samsung. Browsers: Google Chrome
Firefox, Opera.


**After users reviews as result of tests they performed, were applied several changes**.
* Navigation links when they are "active", have a different color and size.  Before color and size were changing only with hover.
* Size of the main picture, a font size of navigation links, footer elements, logo image in the navigation bar have a breakpoint (min-width:992px). Before the size of these elements didn't change. Changes were made by adding media queries for these elements in the CSS code
* Was removed a "Target_blank" element From Modal section of HTML and from booking form on "Contact" page. Now "Thank you" page opening in the same tab. Before were opening too many tabs. *I didn't find another solution now. Can be added another option in the future*. 

### Users stories were tested manually:

* Information about concerts. Dates and locations:

Go to the "Contact" page. 
 Check out Tour dates section, for upcoming concerts. With dates and locations names.

* To make a booking for privet events:
 
 Go to the "Contact" page. 
 Fill a booking form with correct information. 

* Read information about the band and band members:

Go to the "Home" page.
 Check the section "About the Monkees". To read more follow the links to Wikipedia.

* Visit a website regularly by following a link from the newsletter, to read fresh information and updates:
   
   On any page, click a "Sign Up" link. 
   Fill the form with a valid e-mail address. 
   A subscribed user will receive a newsletter on his mail. (left to implement)

* Listen to hits, watch videos:
  
  Go to the "Music" page. 
  Press "Play" to play audio or video. 
  Adjust the volume level. 
  Press "Pause" to stop.

* To see on the web site actual social links:
 
    Check the bottom of the page
   Click on the icon: Facebook, Twitter or Youtube and follow the link in the new tab

* Photos
          Go to the "Gallery" page
           Click on the download icon to save a photo on the computer
          Click on photo to open it in the new tab.

## Deployment

The website was created using the Cloud9 IDE. Git was used for version control and pushed to a repository hosted on GitHub using Ubuntu / Bash script. 
* I created a  GitHub repository https://github.com/AnnaDK/Milestone1
* I initialised git from the Cloud9: *git init*
* To add files was using: *git add .*
* I used commit command: *git commit -m " *description of files or changes* "*
* To push files I used command : *git push* 
* In GitHub repository I opened a settings and selected **the master branch** my website is published at https://annadk.github.io/Milestone1/

Repository : https://github.com/AnnaDK/Milestone1

## Credits

The content in index.html  "About the Monkees", articles about members and content on music.html  "Discography” were taken from 
[Wikipedia](https://en.wikipedia.org/wiki/The_Monkees)


The content in the contact.html section "Tour dates" and part from the text in index.html, side section was taken from 
[monkees.com](https://www.monkees.com/)

Images
Part of the images was provided by Code Institute. from Google images using the Advanced Search and selecting “free to use and share".
Video
From official "The Monkees" [youtube page](https://www.youtube.com/user/themonkees).

I'm thankfull: 
* to my mentor Spencer Barriball for helping me solve some problems and pointing on my mistakes while I was working on the website.
* to the Slack community. I found much useful information in discussions there.

The inspiration I found checking webpages from the different music bands from '60s '70s '80s and from lessons and challenges I had in Code Institute.
