# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://github.com/ramikoff/card-component)
- Live Site URL: [Add live site URL here](https://ramikoff.github.io/card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

- Responsive design
- CSS Flexbox 
- filter: opacity
- How to  make footer stay at bottom of the page


Some CSS code I'm proud of:


```css
* {
  box-sizing: border-box;
}

.page {
  overflow: hidden;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.cards {
  display: flex;
  justify-content: space-between;
  padding-right: 60px;
}

img {
  border-top-right-radius: 5px;
  border-bottom-right-radius: 5px;
  float: left;
  filter: opacity(0.5);
}

.footer {
  margin-top: auto;
}
```


### Continued development

I want to continue focusing on: CSS Flex, Grid, mobile first approach and React in future projects. These are concepts i am still not completely comfortable with or techniques i found useful that i want to refine and perfect.



## Author

- Linkedin - [Ramil Novruzov](https://www.linkedin.com/in/ramilnovruzov/)
- Frontend Mentor - [@ramikoff](https://www.frontendmentor.io/profile/ramikoff)






