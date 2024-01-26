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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Social links profile challenges from Frontend Mentor using Plain CSS.

### Screenshot

(./assets/screenshot.png)

### Links

- Solution URL: (https://github.com/amersfoort3232/Social-Link-Profile)
- Live Site URL: (https://amersfoort3232.github.io/Social-Link-Profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

You must not do this on the body:

```
  height: 100vh;
  width: 100vw;
```

Use min-height not height, and don't set a width at all, especially not 100wv. What you are actually saying there is "I want this to be fill width PLUS the width of s scrollbar when it is present". It can only ever cause bugs for some users when used like this.

- use width not max width on the component, and this should be in rem. Then it will be responsive for all screen sizes and will look good for all users including those with larger default font sizes

-Use gap when using flex

-It is invalid html to have any other direct children except list items in a list

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [resource 1](https://fedmentor.dev/posts/font-size-px/) - This helped me for learning why not to you px, but rem instead.


## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/amersfoort3232)

