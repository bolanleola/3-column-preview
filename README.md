# 3-column-preview
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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)




## Overview

### The challenge

Users will be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

(./screenshot.jpeg)


### Links

- Solution URL: 
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I was able to understand the use of flex box and media queries to ensure the website is responsive.

```CSS Media Query
    @media (max-width: 800px) {
    .container {
      flex-direction: column;
    }
    .sedans{
      border-radius: 15px 15px 0px 0px;
    }
    .luxury{
      border-radius: 0px 0px 15px 15px;
    }
  }
```
```flexbox
.container {
    display: flex;
    margin: 100px;
    justify-content: center;
    flex-direction: row;
  }
  .container > div {
    flex: 1; /*grow*/
  }
 
```


### Continued development


### Useful resources

- (https://www.w3schools.com) 
- (https://www.stackoverflow.com)



## Author
- Frontend Mentor - [@omobolanle](https://www.frontendmentor.io/profile/omobolanle)
- LinkedIn - https://www.linkedin.com/in/omobolanle-oladipo-6b8922102/


