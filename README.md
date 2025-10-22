# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](assets/images/screenshot.png)

### Links

- Solution URL: [Responsive Huddle Landing Page – Mobile & Desktop](https://www.frontendmentor.io/solutions/responsive-huddle-landing-page-mobile-and-desktop-9HtbCNj3Ij)
- Live Site URL: [GitHub Pages](https://outstandinggirl13.github.io/huddle-landing-page-with-single-introductory-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

1. I liked how I took a different approach for mobile and desktop layouts when using background images. On mobile, I applied `bg-mobile.svg` with `background-size: contain` to make it fit neatly within the viewport. For desktop screens (from 1024px), I replaced it with `bg-desktop.svg` and positioned it at the top left for a wider visual effect. This contrast between mobile and desktop backgrounds created a more polished and responsive design.

2. I also liked how I adjusted the `margin-bottom` for `.footer__social` between 900px and 1024px using the `clamp()` function. It helped the background image align better on medium screens and made the layout feel smoother between breakpoints.

### Useful resources

- [Google Webfonts Helper](https://gwfh.mranftl.com/fonts) – This tool helped me easily self-host web fonts and generate the correct `@font-face` CSS with all required formats.

## Author

- Website - [Outstandinggirl13](https://github.com/Outstandinggirl13)
- Frontend Mentor - [@Outstandinggirl13](https://www.frontendmentor.io/profile/Outstandinggirl13)