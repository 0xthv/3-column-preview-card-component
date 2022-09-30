# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### Links

- Solution URL: [Solution URL here](https://beamish-bavarois-c59c77.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Mix-blend-mode and setting a transparent border to avoid the slight layout ajustment when hovering over the button:

```css
  border: 2px solid transparent;
  mix-blend-mode: lighten;

  ....
  on hover:
  border: var(--secondary-BckHeaBtn) solid 2px;
```

### Useful resources

- [Mix-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode#:~:text=The%20mix%2Dblend%2Dmode%20CSS,parent%20and%20the%20element's%20background.) - Instead of using fixed colors on the button, i've used the mix-blend-mode.

## Author

- Frontend Mentor - [@0xthv](https://www.frontendmentor.io/profile/0xthv)
