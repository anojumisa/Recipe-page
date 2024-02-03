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
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![Recipe Page](../images/Result-screenshot.png)

### Links

- Solution URL: [recipe-github-page](https://github.com/anojumisa/Recipe-page)
- Live Site URL: [recipe-page](https://anojumisa.github.io/Recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Block
For styles

### What I learned

I built this project using HTML with CSS block. I use <span> elements to target bold font in multiple sections of the page. 

Table Formatting Challenges and Solutions:

Initial Goal: 
- Create a table with only the outer outline visible.
- Challenge: Ensuring seamless table appearance without whitespace gaps.

Solutions:

Removed bottom border:
```css 
table tr:nth-last-child(1) td {
  border-bottom: none;
  }
```

Eliminated whitespace: 
```
border-collapse: collapse;
```

### Continued development

I am going to intensely focus on mastering Flexbox and CSS Grid to create more dynamic and adaptive layouts.

## Author

- Website - [Ano Jumisa](https://www.anojumisa.com)
- Frontend Mentor - [@anojumisa](https://www.frontendmentor.io/profile/anojumisa)
- Twitter - [@anojumisa](https://www.twitter.com/anojumisa)
