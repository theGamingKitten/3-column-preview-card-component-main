# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshots

![](./screenshot.jpg)

![](./screenshot_mobile.jpg)

### Links

- [Solution](https://github.com/theGamingKitten/3-column-preview-card-component-main)
- [Live Site](https://thegamingkitten.github.io/3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- [SASS](https://sass-lang.com/)

### What I learned

First time using SASS, as I wanted to try something like this and thought the nesting for the individual cards is a great opportunity to do this.

Used this mixin to save a lot of code to style the buttons:
```css
@mixin theme($theme: DarkGray) {
    background-color: $theme;
    .btn {
        color: $theme;
    }
}
```
Will definitely try to use it more in future challenges

### Useful resources

- [SASS Guide](https://sass-lang.com/guide/) - Used the guide for SASS to make my first steps with it

## Author

- Frontend Mentor - [@theGamingKitten](https://www.frontendmentor.io/profile/theGamingKitten)