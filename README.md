# 3-column-preview-card-component

![](./design/desktop-preview.jpg)

# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


### Links

- Solution URL: https://github.com/HIT2k1/3-column-preview-card-component
- Live Site URL: https://hit2k1.github.io/3-column-preview-card-component/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

- To avoid increasing the width or the height of the button when adding border to it, I did the following:
```css
.card-button {
  display: inline-block;
  padding: 1.5rem 3rem;
  border: 2px solid transparent;
}
.card-button:hover {
  border-color: #f2f2f2;
}
```

## Author

- Frontend Mentor - @HIT2k1
