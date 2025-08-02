# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screenshot.png)

### Links

- Solution URL: [Git Repo](https://github.com/bmarius05/FrontendMentorSocialLinks)
- Live Site URL: [Git page](https://bmarius05.github.io/FrontendMentorSocialLinks/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

Learned to modify a components style when it is hovered over.

```css
.card{
    background-color: var(--Grey-800);
    border-radius: 10px;
    padding: 40px;
    max-width: 350px;
    margin: auto;
    display: flex;
    flex-direction: column;
    gap:0;
    align-items: center;
}
```
```css
.social a{
    text-align: center;
    text-decoration: none;
    font-size: 16px;
    font-weight: 600;
    color: var(--White);
    background-color: var(--Grey-700);
    padding:16px 100px;
    border-radius: 5px;
    transition: all .75s ease;
}
.social a:hover{
    background-color: var(--Green);
    color: var(--Grey-900)
}
```

## Author

- Frontend Mentor - [@bmarius05](https://www.frontendmentor.io/profile/bmarius05)
- Twitter - [@bmarius05](https://x.com/bmarius05)
