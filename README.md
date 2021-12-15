# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshots

![](./screenshots/screenshot1.png)

![](./screenshots/screenshot2.png)

### Links

- Solution URL: [frontendmentor.io](https://www.frontendmentor.io/solutions/responsive-stats-preview-card-component-using-css-flexbox-0ZRvfheiw)
- Live Site URL: [carltonmpofu.github.io](https://carltonmpofu.github.io/responsive-stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this project, I learned about CSS Grid and Flexbox but decided only to use Flexbox since it works better for one-dimensional layouts. I had some challenges getting the image to fill the div container. But, I managed to get it to work using the code sample below.

```html
<div class="card-image">
  <div class="image-desktop">
  <img  src="image=path" alt="">
  </div>
  <div class="image-mobile">
  <img  src="image=path" alt="">
  </div>
</div>

```

```css
.image-desktop {
  height: 100%;
}

.image-mobile {
  height: 100%;
}

img {
  width: 100%;
  height: 100%;
  display: block;
}
```

### Continued development

In future projects, I want to make use of CSS grid and flexbox more to improve my knowledge and skills when it comes to the two modules.

### Useful resources

- [A guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is a fantastic guide that helped me understand how flexbox works. I'd recommend it to anyone looking for a comprehensive guide that explains everything about flexbox.

- [W3Schools CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) - This helped me practice using flexbox properties and familiarize myself with the layout module.


## Author
- Frontend Mentor - [@CarltonMpofu](https://www.frontendmentor.io/profile/CarltonMpofu)
