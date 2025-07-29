# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Mobile:

![.images/Screenshot NFT preview card component Mobile.png](.images/Screenshot%20NFT%20preview%20card%20component%20Mobile.png)

Browser:

![.images/Screenshot NFT preview card component Browser.png](.images/Screenshot%20NFT%20preview%20card%20component%20Browser.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

-Exploring clamp() min() max()
-Overlay image and background on hover


```css
.header-img-container::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: max(100%, 18vw);
  height: 100%;
  background-color: var(--Cyan-400);
  border-radius: 10px;
  opacity: 0;
  transition: opacity 0.3s ease;
}

/* Position of view icon */
.view-icon {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 10%;
  height: auto;
  transform: translate(-50%, -50%);
  z-index: 1;
  opacity: 0;
  transition: opacity 0.3s ease;
}
```


### Continued development

Continue Practice with clamp() min() max()


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@StiTchD-WireD](https://www.frontendmentor.io/profile/StiTchD-WireD)
