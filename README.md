# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
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

![Design preview for the Product preview card component coding challenge](./design/Screenshot%202023-02-16%20121921.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/hschu91466/product-preview-card-component-main)
- Live Site URL: [Add live site URL here](https://hschu91466.github.io/product-preview-card-component-main/#)

## My process

### Built with

- HTML5 markup
- Sass
- CSS custom properties
- Flexbox
- Bootstrap Grid
- Mobile-first workflow

### What I learned

Relearned Sass and remembered what I really liked about it.

It took me way too long to get everything lining up correctly in both the mobile and the desktop view.  I am still not entirely happy with the side image.  
I finally figured out how to evenly space the rows in the text section of the card using flex-direction.  Lining up the current and previous price was also a challenge.
I learned how to do a git-commit from VSCode.

.card-body {
        display: flex;
        flex-direction: column;
        max-height: 80dvh;
    }
    .contents {
        padding: 1.2em 1.2em;
        flex: 1;
    }

### Continued development

I really want to get the layout down pat.  I am going to do some futher study into flexbox.  Also the bootstrap equivilent.

### Useful resources

- [Learn Sass in 20 minutes](https://www.youtube.com/watch?v=Zz6eOVaaelI&t=793s) 
- [Getting Started with Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/) 

## Author

- Website - [Holly Schu](http://hollyschu.com/)
- Frontend Mentor - [@yhschu91466](https://www.frontendmentor.io/profile/hschu91466)

