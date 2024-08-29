## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/screenshot.jpg)

### Links

- Solution URL: [[Social Link Profile Main](https://franciscomi.github.io/social-links-profile-main)] 

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

  Flexbox is very useful when we want to centre an html element as horizontally, easy :-) , or vertically, not too easy :-( 

  Flexbox distributes the elements with respect to two axes

  ![[flex container] https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Flexbox/flex_terms.png]

  **BASIC HTML STRUCTURE**.
  
  We use the <body> element as the main container and add a <section> element as a child container.

  ```html
  <body class="card-flex">
    <section id="card" class=" card card--section card__align">
      <!-- El código viene aquí -->
    </section>
  <body>
  ```
  
  **BASIC CSS STRUCTURE**.

  And now we can touch the CSS! The class ‘card-flex’ in the <body> sets flexbox 

  ```css
  .card-flex{
    display:flex;
    align-items: center; /* Centra verticalmente (cross axis) */
    justify-content: center; /* Centra horizontalmente (main axis)*/
    flex-direction: column; 
  }

  .card__align{
    text-align: center; /* Centra el texto del contenedor */
  }  
  ```


### Useful resources

- [W3C Markup Validation Service](https://validator.w3.org/) - This URL helped me to validate the HTML code correctly
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) - This URL help me to validate CSS. It also allows you to download the icon. :-D


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
