# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

Desktop:
![Desktop initial state](/design/comp-challenge-desktop-init.png)

Mobile: 

![Mobile initial state](/design/comp-challenge-mobile-init.png)

### Links

- [Live Site URL](https://huddle-landing-pg-ianwilk20.netlify.app/design/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

- I learned how to define colors as variables in CSS. Here is an example of how to define color variable and use it in a class:

  ```CSS
  :root {
      --dark-blue: hsl(192, 100%, 9%);
  }

  .my-class {
    color: var(--dark-blue)
  }
  ```

- I was having trouble with some of the images overflowing their parent elements. What helped was adding this to my CSS to see the borders of elements and what exactly was causing the overflow:

  ```CSS
  * {
    outline: 1px solid #f00 !important;
    opacity: 1 !important;
    visibility: visible !important;
  }
  ```

- Improvising is necessary. With these challenges we are provided with two mockups, one for the mobile and one for a desktop layout. The in-between sizes of the screen are also important to consider when developing a responsive website. As a result, some creative liberties are necessary for the in-between sizes of this challenge that are not depicted in the mockups.

- The mockups used certain foreground colours that had a low contrast ratio with the background so I made some modifications. For example, the hover state colors for certain elements was below a 2.5 so I altered them to be more perceivable.


### Continued development

Going forward I'm trying to find a way to minimize the amount of CSS I write. Typically I start developing the mobile layout of a site and afterwards move onto designing the standard 1920x1080 desktop layout. Already that requires some media queries. What adds more complexity to the CSS file are the in-between sizes. Most often the in-between sizes need certain customizations to make the site's responsiveness look natural and less like the in-between sizes were forgotten about.

I like that these Beginner and Junior challenges have been developing my HTML, CSS, and JavaScript skills; however, I think that my time has been spent 85% on CSS, 10% on HTML, and 5% on JavaScript. It would be of benefit to me to find future challenges that let me learn JavaScript and HTML more.

### Useful resources

- [Declaring variables in CSS](https://stackoverflow.com/questions/1875852/how-can-i-define-colors-as-variables-in-css) - This helped me learn how to declare variables in CSS for later use in my stylesheet.
- [Preserving aspect ratios of responsive images](https://stackoverflow.com/a/11079048) - As I mentioned, I had trouble with images overflowing. When I tried solving for the overflow it meant the loss of the image's aspect ratio at some screen sizes. I found this helpful post to solve this by declaring a max-width to a pixel or rem amount and setting the width to 100%.

## Author

- GitHub - [ianwilk20](https://github.com/ianwilk20)
