# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [solution URL here](https://67f796e22d64941fa6fe3f46--heartfelt-lily-a79e68.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```css
@media(min-width: 600px) {
    .container {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media(min-width: 1280px) {
    .container {
        grid-template-columns: repeat(4, 1fr);
        max-width: 1200px;
        margin: 50px auto;
    }
    .testimonials.violet {
        grid-column: 1/3;
    }

    .testimonials.blue {
        grid-column: 2/4;
    }

    .testimonials.last {
        grid-column: 4;
        grid-row: 1/3;
    }
}
```


## Author

- Frontend Mentor - [@Til-da](https://www.frontendmentor.io/profile/til-da)


