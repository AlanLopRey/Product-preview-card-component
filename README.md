# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

#### Desktop design

![an image of the of the Gabrielle Essence Fragance for the desktop design ](design\desktop-design.jpg)

#### Mobile design

![an image of the of the Gabrielle Essence Fragance for the Mobile design ](design\mobile-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Media Queries

### What I learned

This was my first project to put my knowledge in CSS on practice
I learn to use the Display flex in a correct way to positon the secundaryPrice element in the same way as the design as well as the cardContainer for the Desktop design and set the box in the middle, I also learned how to change the image for one to other design using the content property

```css
.secundaryPrice {
  display: flex;
  font-family: "Montserrat", sans-serif;
  align-items: center;
  text-decoration: line-through;
  color: var(--Dark_grayish_blue);
}

.cardContainer {
  width: 600px;
  height: 450px;
  display: flex;
  /* flex-direction: row; */
  margin-top: 175px;
  margin-left: auto;
  margin-right: auto;
}

.containerImage {
  content: url(../images/image-product-desktop.jpg);
}
```

### Continued development

learn how to size the fonts because I feel that was the only thing I fail in this project
keep practice using the flexbox.

## Author

- Frontend Mentor - [@AlanLopRey](https://www.frontendmentor.io/profile/AlanLopRey)
