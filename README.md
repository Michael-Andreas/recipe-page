# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./assets/images/Screenshot%20Mobile.png)

![](./assets/images/Screenshot%20Desktop.png)

### Links

- Solution URL: [github.com/Michael-Andreas/recipe-page](https://github.com/Michael-Andreas/recipe-page)
- Live Site URL: [michael-andreas.github.io/recipe-page/](https://michael-andreas.github.io/recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

How to make custom ordered and unordered list indicators:

```css
ol {
  list-style: none;
  counter-reset: num;
  padding-left: 0.5rem;
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}

ol li {
  counter-increment: num;
  display: flex;
}

ol li::before {
  content: counter(num) ".";
  color: var(--rose-800);
  font-weight: bold;
  display: block;
  flex-shrink: 0;
  margin-right: 1rem;
}
```

## Author

- Website - [michaelandreas.de](https://michaelandreas.de)
- Frontend Mentor - [@Michael-Andreas](https://www.frontendmentor.io/profile/Michael-Andreas)
