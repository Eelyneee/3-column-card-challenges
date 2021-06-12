# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](C:\Users\user\Desktop\Front end challenges\3-column-card-solution\screencapture-2021-06-12-18_03_30.png)

### Links

- Solution URL: https://github.com/Eelyneee/3-column-card-challenges
- Live Site URL: https://eelyneee.github.io/3-column-card-challenges/

## My process

### Built with

- CSS custom properties
- Flexbox
- Media queries

### What I learned

In this challenge, I how to make the website responsive using media queries.

```css
 @media only screen and (min-width: 750px) {
        .box {
          flex-direction: row;
        }
        .card1 {
          border-radius: 10px 0px 0px 10px;
        }
        .card3 {
          border-radius: 0px 10px 10px 0px;
        }
} ;
```


### Useful resources

- [Media Queries Demystified: CSS Min-Width and Max-Width](https://www.emailonacid.com/blog/article/email-development/emailology_media_queries_demystified_min-width_and_max-width/) - This helped me for clear my doubts on min-width and max-width. I'd recommend it to anyone still learning this concept.

## Author

- Website - https://www.linkedin.com/in/eelynelow/
- Frontend Mentor - [@Eelyneee](https://www.frontendmentor.io/profile/Eelyneee)
- Email - eelyne99@gmail.com
