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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Screenshot](./screenshot.jpg)


### Links

- Solution URL:[solution URL](https://github.com/Wasline/product-preview-card-component-main)
- Live Site URL:[live site](https://sensational-daifuku-008f3d.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I saw a lot of the links between the images and the media queries via html in <img>.

```html
 <img srcset="images/image-product-desktop.jpg 600w, images/image-product-mobile.jpg 686w"
        sizes="(max-width: 600px) 686px, 300px" src="images/image-product-desktop.jpg" alt="A bottle of perfume">
```
```css
@media only screen and (max-width: 600px) {
    section {
        flex-direction: column;
        width: 300px;
    }
    .prices {
        margin-top: -1px;
        margin-bottom: 10px;
    }

    img {
        width: 100%;
        border-top-left-radius: 20px;
        border-top-right-radius: 20px;
        border-bottom-left-radius: 0px;
       }
  }
```

### Continued development

The things I want to improve and review are the media queries, during this challenge I saw that there were several (@media, @media only, @media screen).

### Useful resources

Stackoverflow 😁

## Author

- Website - [Wasline Saint Fleur](https://www.waslinesaintfleur.com)
- Frontend Mentor - [@Wasline](https://www.frontendmentor.io/profile/Wasline)
- Twitter - [@sfwawa](https://www.twitter.com/sfwawa)