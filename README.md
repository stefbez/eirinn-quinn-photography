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

Mockups created as the first stage of planning the website can be found (here)[/mockups/mockups.pdf]

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


## Technologies Used

## Testing

Once the [home page](https://stefbez.github.io/eirinn-quinn-photography/index.html) had been completed I tested it on multiple devices. 
I work on a mac using OS X and the deployment of the website worked exactly as expected.
I opened the webpage on android phone and it worked as expected. When I opened it on an iPhone I came across an issue with the `selling-bg` image. 
After a bit of research I found that there is a known issue with iOS displaying `background-attachment: fixed`.
I found a solution for this issue at (https://github.com/thesved/fixed-cover-background). 
After reading and understanding what they had done to fix the issue I implemented their code and modified it slightly to work with my site. 
I do not take credit for their work and have noted this in my css document around the code and in the credits section of the README.md document.
The other option instead of keeping the same feature, so that it would display in an aesthetically pleasing way would be to remove `background-attachment: fixed` all togther.

Testing the home page once completed, the word 'photography' was still hyphenating on iPhone X and other mobile sized screens when using safari. Added ```-webkit-``` and ```-moz-``` variants so that it would work as expected on safari and firefox.

Tested all HTML pages and CSS on the (HTML validator website)[https://validator.w3.org/] and (CSS validator website)[http://www.css-validator.org/].

## Deployment

The website can be found on the link at the top of the page and [here](https://stefbez.github.io/eirinn-quinn-photography/). I deployed the project using GitHub Pages. At the moment the deployed version uses the master branch, but if future updates are needed these can be done using a separate branch until all updates are tested thoroughly and can be deployed.

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

* The footer needed to be pushed down to the bottom on some screen sizes, such as iPad pro. I found a way to do this through some research online and used [https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/) to fix this issue. The code used from this website is not my own work, but a solution to a problem I was having.

* (Bootstrap)[https://getbootstrap.com/docs/4.4/getting-started/introduction/] was used throughout the site, including the (carousel)[https://getbootstrap.com/docs/4.2/components/carousel/] for the home and portfolio page; (modal)[https://getbootstrap.com/docs/4.4/components/modal/] for the portfolio page and the (forms)[https://getbootstrap.com/docs/4.4/components/forms/] and (submit button)[https://getbootstrap.com/docs/4.4/components/buttons/] on the contact page.

* (Font Awesome)[https://fontawesome.com/icons?d=gallery] icons were used in the footer of every page and the envelope icon on the contact page

* The CDN's for Bootstrap and Font Awesome were found (here)[https://www.bootstrapcdn.com/]

### Media

* All images were taken and are owned by Eirinn Quinn, who gave me the inspiration to make the website

### Acknowledgements

* I received inspiration from (Two-D Photography's website)[https://www.two-d.co.uk/]