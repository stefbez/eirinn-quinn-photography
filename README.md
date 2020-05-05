# Eirinn Quinn Photography
## Milestone Project 1

The project can be found [here](https://stefbez.github.io/eirinn-quinn-photography/).

As part of the Code Institute Full Stack Developer Diploma I have created this website using all of the technologies learnt throughout the course so far.

This website showcases the very best work of a talented band photographer, Eirinn Quinn. This website has been created so that bands looking for a photographer for their upcoming gigs and concerts, album artwork or looking to do a photoshoot and get portaits done can see her work and book her to work with them.

The website has been created with her photography style in mind, lots of moody, black and white, and darker images are on show and the style of the website matches that perfectly.

## UX

The UX process was vital to creating a good website that could do it's designed purpose perfectly. The purpose of the project from the photographers side was to show off the types of photography that she does, to show off her best work and to be contactable for work. With all of this in mind the users experience and expectations could be guaged. 

I used trello to create user stories that are relevant to what each type of user expects and wants from this type of website. The aim is to please every user that visits this site, make it easy to use and ultimately make them interested enough in the photographer's work that they get in contact.

## Features

## Technologies Used

## Testing

Once the [home page](https://stefbez.github.io/milestone-project-1/index.html) had been completed I tested it on multiple devices. 
I work on a mac using OS X and the deployment of the website worked exactly as expected.
I opened the webpage on android phone and it worked as expected. When I opened it on an iPhone I came across an issue with the `selling-bg` image. 
After a bit of research I found that there is a known issue with iOS displaying `background-attachment: fixed`.
I found a solution for this issue at (https://github.com/thesved/fixed-cover-background). 
After reading and understanding what they had done to fix the issue I implemented their code and modified it slightly to work with my site. 
I do not take credit for their work and have noted this in my css document around the code and in the credits section of the README.md document.
The other option instead of keeping the same feature, so that it would display in an aesthetically pleasing way would be to remove `background-attachment: fixed` all togther.

## Deployment

The website can be found on the link at the top of the page and [here](https://stefbez.github.io/eirinn-quinn-photography/). I deployed the project using GitHub Pages. At the moment the deployed version uses the master branch, but if future updates are needed these can be done using a separate branch until all updates are tested thoroughly and can be deployed.

## Credits

### Content
* The below code in `style.css` was found [here](https://github.com/thesved/fixed-cover-background), used and edited to work with my page and to fix an error on iOS devices specified above.
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
### Media

* All images were taken and are owned by Eirinn Quinn, who gave me the inspiration to make the website
