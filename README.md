# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./images/screenshot-desktop.png)
![](./images/screenshot-mobile.png)

### Links

- Solution URL: [Portfolio](https://gelatodigital.com/#portfolio)
- Live Site URL: [https://rodrigo-social-proof-section.netlify.app/](https://rodrigo-social-proof-section.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This was a good example of nth-of-type usage. It creates the stair looking alignment for the itens with different backgrounds
```css
    .buyer-review:nth-of-type(3){
        margin-top: 10vh;
    }
```
It also highlighted how easy it is to refactor mobile first designs if you plan them ahead before working on css

.

Also, when adding the google font, I can link all font weights on the same link. Just pay attention of the google fonts website and click the + button on the weights you want instead of creating 3 different links
```html
<link href="https://fonts.googleapis.com/css2?family=Spartan:wght@400;500;700&display=swap" rel="stylesheet">
```


### Continued development

Still not happy with the i-pad width screen size, maybe I should pay for hte premium subscription?

Got to keep prioritizing speed over pixel perfection. Pixel perfection is a trap habbit that only subtracts time from more important fundamentals

### Useful resources

https://www.w3schools.com/cssref/sel_nth-of-type.asp
Always helpful to check w3schools

## Author

- Website - [Rodrigo Tebaldi](https://www.gelatodigital.com)
- Frontend Mentor - [@Rod-Barbosa](https://www.frontendmentor.io/profile/Rod-Barbosa)

