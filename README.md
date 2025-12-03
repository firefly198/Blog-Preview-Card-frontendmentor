# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](assets/images/Screenshot%202025-12-04%20011710.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Variable font (Figtree)
- CSS clamp() for responsive font sizes


### What I learned

I learnt how to add downloaded fonts to design and how to reduce font size for smaller screens without using media queries. Also, Figma is very good.


```css

  @font-face {
    font-family: "Figtree";
    src: url("assets/fonts/Figtree-VariableFont_wght.ttf") format("truetype");
    font-weight: 100 900;
    font-style: normal;
}

  h1 {
    font-size: clamp(20px, 1.6vw, 24px);
    font-weight: 800;
}

```


### Useful resources

- [resource 1](https://www.w3schools.com/) - This helped me to learn HTML & CSS
- [resource 2](https://www.frontendmentor.io/) - Thanks for advices and projects

## Author


- Frontend Mentor - [firefly198](https://www.frontendmentor.io/profile/firefly198)


