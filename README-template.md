# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Need to build responsive layout for mobile and desktop device
- Getting the image overlay effect accurate
- Figuring out the dimensions and font sizes

### Screenshot

![](screenshot/mobile.jpg)
![](screenshot/desktop.jpg)


### Links

- Solution URL: (https://github.com/khazin/stats-preview-card-component)
- Live Site URL: (https://khazin.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
.container {
  width: 100vw;
  /*mobile*/
  min-width: 375px;
}
.image::before {
  content: "";
  position: absolute;
  top: 0px;
  right: 0px;
  bottom: 0px;
  left: 0px;
  background-color: rgba(170, 92, 219, 0.801);
}
@media screen and (min-width: 1400px) {
  .container {
    max-width: 100vw;
  }
}
```

### Continued development

- Getting the image overlay effect as accurate
- Getting the width, height and fonts as accurate

### Useful resources

- [w3schools](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) - This helped me to write media queries and responsive layout.
- [w3schools](https://www.w3schools.com/cssref/pr_dim_min-width.asp) - This helped me to write media queries and responsive layout.

## Author

- Frontend Mentor - [@khazin](https://www.frontendmentor.io/profile/khazin)
- github - [@khazin](https://github.com/khazin)
