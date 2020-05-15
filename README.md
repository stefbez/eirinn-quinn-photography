# Eirinn Quinn Photography

## Milestone Project 1

The project can be found [here](https://stefbez.github.io/eirinn-quinn-photography/).

As part of the Code Institute Full Stack Developer Diploma I have created this website using all of the technologies learnt throughout the course so far.

This website showcases the very best work of a talented band photographer, Eirinn Quinn. This website has been created so that bands looking for a photographer for their upcoming gigs and concerts, album artwork or looking to do a photoshoot and get portaits done can see her work and book her to work with them.

The website has been created with her photography style in mind, lots of moody, black and white, and darker images are on show and the style of the website matches that perfectly.

## UX

The UX process was vital to creating a good website that could do it's designed purpose perfectly. The purpose of the project from the photographers side was to show off the types of photography that she does, to show off her best work and to be contactable for work. With all of this in mind the users experience and expectations could be guaged. 

I used trello to create user stories that are relevant to what each type of user expects and wants from this type of website. The aim is to please every user that visits this site, make it easy to use and ultimately make them interested enough in the photographer's work that they get in contact.

### User stories

* As a user I want to see if the photographer is local to me before contacting so that I don't waste time enquiring if they are too far away
* As a user I want an easy to use navigation bar to see all parts of the website with ease
* As a user I want to see what the photographer has to offer from the first look of the home page so that I'm drawn in to look at the rest of the website
* As a user I want to read about the photographer to see if I want to work with them
* As a user and social media user I want to explore the photographers social media to see more about the photographer and their work
* As a user I want to explore a gallery of the photographers work to see what the photographer could offer me if I hire
* As a user I want to be able to contact the photographer to discuss hiring

These user stories justify every section of the site and forced a slight change in design from the original mockups. The footer now features a location link to google maps whereas the mockup didnt consider this.

### Mockups

Mockups created as the first stage of planning the website can be found [here](/mockups/mockups.pdf)

## Features

### Current Features

* Header image with website name allows all users to know what site they're on, remember the name and also link back to the home page easily.
* Navbar allows all users to easily navigate the site whether on mobile, tablet or desktop.
* The location in the footer allows potential customers to see where Eirinn is based and if her location is close enough for them to work together, using a link to google maps allows potential customers the ease to see where she is located.
* Social links in the footer allow social media users and potential customers the ability to follow, add or join her pages and see updates as she posts them which could create more business for her.
* Home page headers and images allow all users entering the site to quickly understand the type of work that Eirinn does to see if she is the right type of photographer for them.
* The reviews on the carousel allow potential customers the chance to see what multiple previous customers think of her work without having to scroll through multiple pages of reviews.
* The gallery on the portfolio page allows potential customers the chance to see a selection of her best work which allows them to decide if they like her work enough to work with her.
* The Modal Carousel allows users to see the full image and get a better view of the images displayed in the gallery.
* Contact form allowing users to enquire about working with Eirinn

### Future Features - to implement

* Embed social feed from instagram on portfolio page for constantly updated photos
* Using JavaScript, allow contact forms to work fully

## Technologies Used

* [HTML](https://en.wikipedia.org/wiki/HTML) - Makes up the basis for the page. All of the visible text, the images in the gallery and the forms on the contact page
* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - Styling for the whole site, from backgrounds to text fonts, sizes and colors. Spacing throughout the site, animations and color changes on hover and click
* [Bootstrap 4.4.1](https://getbootstrap.com/docs/4.0/getting-started/introduction/) - The framework that provides basic styling and objects that I built upon. Especially useful on the portfolio page where i utilised Bootstrap's modal and carousel features
* [Font Awesome](https://fontawesome.com/icons?d=gallery) - Provided the social links on the footer and the envelope on the contact page. Easy to recognise icons that take away the need for lengthy names of social media pages
* [Google Fonts](https://fonts.google.com/) - Chose the fonts carefully from Google Fonts and embedded them to the CSS page and used the throughout the site
* [Google Maps](https://www.google.co.uk/maps/) - Embedded a map into the contact page which allows users to browse a map of the location of the showroom witihin the site. Also included a link in the footer allowing users to view the photographers location on the google maps website

## Testing

Once the [home page](https://stefbez.github.io/eirinn-quinn-photography/index.html) had been completed I tested it on multiple devices. 
I work on a mac using OS X and the deployment of the website worked exactly as expected.
I opened the webpage on android phone and it worked as expected. When I opened it on an iPhone I came across an issue with the `selling-bg` image. 
After a bit of research I found that there is a known issue with iOS displaying `background-attachment: fixed`.
I found a solution for this issue at [https://github.com/thesved/fixed-cover-background](https://github.com/thesved/fixed-cover-background). 
After reading and understanding what they had done to fix the issue I implemented their code and modified it slightly to work with my site. 
I do not take credit for their work and have noted this in my css document around the code and in the credits section of the README.md document.
The other option, instead of keeping the same feature, so that it would display in an aesthetically pleasing way would be to remove `background-attachment: fixed` all togther.

Images found to be taking a while to load across the whole site. Reduced the image sizes and re-uploaded them into the project. Tested again and found they load much quicker, viewing the website now doesnt require a wait.

Testing the home page once completed, the word 'photography' was still hyphenating on iPhone X and other mobile sized screens when using safari. Added `-webkit-` and `-moz-` variants so that it would work as expected on safari and firefox.

Tested all HTML pages and CSS on the [HTML validator website](https://validator.w3.org/) and [CSS validator website](http://www.css-validator.org/). 
A few small errors found, mainly with spacing. The biggest error found was in the footer of every page the `<li>` tag didn't follow the `<ul>` tag. I corrected this throughout all of the html files.
Now when tested every page shows `No errors or warnings to show.`

### Testing across multiple devices and browsers on completion

Developed on a MacBook Pro using GitPod and checked throughout development on Chrome
Tested on the following devices:

* MacBook Pro 13" - Internet Explorer (using Safari developer tools), Safari, Chrome, Edge, Firefox, Opera
* iPhone X - Safari, Chrome, Edge, Firefox, Opera
* Samsung Galaxy A40 - Samsung Browser, Safari, Chrome, Edge, Firefox, Opera

Multiple screen sizes were tested using Chrome developer tools on the MacBook, including Moto G4, Galaxy S5, Pixel 2, iPhone 5/SE, iPhone 6/7/8, iPhone 6/7/8 Plus, iPhone X, iPad, iPad Pro, Desktop and 4K TV screens.

### Testing Process

Testing involved using every feature available on each page across all devices and browsers. 

* All pages
    * The text (Eirinn Quinn Photography) in the heading linked back to the home page
    * Navbar dropped down as expected (if smaller screen size) and all nav links worked and displayed as expected
    * Footer location and social links work as expected
    * Footer is at the bottom of the screen and displays as expected

* Home Page
    * First image is displaying as fixed when scrolling
    * All images and text display as expected
    * Caurousel displays and works as expected

* About Page
    * All text displays as expected
    * Image displays as expected

* Portfolio Page
    * Text displays as expected
    * All images display correctly on the main page and when clicked, appearing in the modal/carousel
    * The carousel works correctly
    * The modal close button works as intended

* Contact Page
    * All text displays as expected
    * Forms allow text and dont allow submission until all required fields are filled
    * Telephone and email links work, especially on mobile devices, launching phone or mail app
    * Embedded map works correctly, is movable and launches the larger map when the link on it is pressed
    * Box shadow displays correctly on the right screen size

#### Issues found on devices and browsers

Very few issues found across all devices, browsers and screen sizes. Images rendered well and all looked as expected and intended.

Issues:

* iPad pro view on chrome developer tools - Content on about, portfolio and contact pages too short to fill page so the footer wasn't displaying on the bottom of the page. **Fixed** this issue with help from this [site](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/)
* iPhone X - Opera, Edge & Firefox - When scrolling up images jumped as the browser taskbar reappeared - **This issue still remains**
* iPhone X - Safari, Chrome, Edge, Firefox, Opera - On contact page when a required field isnt filled in and submit button is pressed the `fill in this field` prompt is off center. As it appears on all tested browsers it could be an iOS issue - **This issue still remains**
* Samsung Galaxy A40 - Samsung Browser - Tall images displaying in the Portfolio page's modal carousel has its close button cut off slightly by the address bar at the top, still fully functional and able to be pressed - **This issue still remains**

## Deployment

I used GitPod to develop the site and GitHub to host it.

The website can be found on the link at the top of the page and [here](https://stefbez.github.io/eirinn-quinn-photography/). I deployed the project using GitHub Pages. At the moment the deployed version uses the master branch, but if future updates are needed these can be done using a separate branch until all updates are tested thoroughly and can be deployed.

### Deployment using GitHub Pages

1. Go to the [repository](https://github.com/stefbez/eirinn-quinn-photography)
2. Under the repo name go to settings
3. Scroll down to the GitHub Pages section
4. Select a publishing source which is the master branch
5. Check for confirmation text in a green banner saying `Your site is published at https://stefbez.github.io/eirinn-quinn-photography/`
6. The site is now live on GitHub Pages

I followed this handy guide by [GitHub](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

### Clone Eirinn Quinn Photography

1. Go to the [repository](https://github.com/stefbez/eirinn-quinn-photography)
2. Click on the green `Clone or download` button
3. Copy the URL - (https://github.com/stefbez/eirinn-quinn-photography.git)
4. Using the terminal in GitPod paste the code `git clone https://github.com/stefbez/eirinn-quinn-photography.git`
5. The whole repository folder, including all files is now available for use

## Credits

### Content

* The below code in `style.css` was found at [https://github.com/thesved/fixed-cover-background](https://github.com/thesved/fixed-cover-background), used and edited to work with my page and to fix an error on iOS devices specified above.
*I do not take credit for this work below and declare that it is not all my own work, but used as a solution for a common issue on iOS.*

```css
.selling-bg:after{
      content:"";
      position:fixed; /* stretch a fixed position to the whole screen */
      top:0;
      height:100vh; /* fix for mobile browser address bar appearing disappearing */
      left:0;
      right:0;
      z-index: -1;  /* needed to keep in the background */
      background: url(../images/sinka-oneils.jpg) center top no-repeat;
      -webkit-background-size: cover;
      -moz-background-size: cover;
      -o-background-size: cover;
      background-size: cover;
}
```

* The footer needed to be pushed down to the bottom on some screen sizes, such as iPad pro. I found a way to do this through some research online and used [https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/) to fix this issue. The code used from this website is not my own work, but a solution to a problem I was having

* The info and code needed to hyphenate the word 'Photography' on the home page was found here [https://developer.mozilla.org/en-US/docs/Web/CSS/hyphens](https://developer.mozilla.org/en-US/docs/Web/CSS/hyphens)

* [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/) was used throughout the site, including the [carousel](https://getbootstrap.com/docs/4.2/components/carousel/) for the home and portfolio page; [modal](https://getbootstrap.com/docs/4.4/components/modal/) for the portfolio page and the [forms](https://getbootstrap.com/docs/4.4/components/forms/) and [submit button](https://getbootstrap.com/docs/4.4/components/buttons/) on the contact page

* [Font Awesome](https://fontawesome.com/icons?d=gallery) icons were used in the footer of every page and the envelope icon on the contact page

* The CDN's for Bootstrap were found on [BootstrapCDN](https://www.bootstrapcdn.com/) and directly from [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/download/) 

* The CDN for Font Awesome was found [here](https://fontawesome.com/how-to-use/customizing-wordpress/snippets/setup-cdn-webfont)

* Fonts were found and embedded from [Google Fonts](https://fonts.google.com/)

* Map embedded on the contact page and linked to in the footer uses [Google Maps](https://www.google.co.uk/maps/)

### Media

* All images were taken and are owned by Eirinn Quinn, who gave me the inspiration to make the website

### Acknowledgements

* I received inspiration from [Two-D Photography's website](https://www.two-d.co.uk/)