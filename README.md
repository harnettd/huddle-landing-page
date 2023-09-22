# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshots

![screenshot-mobile1](./images/screenshot-mobile1.png) 
![screenshot-mobile2](./images/screenshot-mobile2.png)
![screenshot-desktop](./images/screenshot-desktop.png)

### Links

- Solution URL: [https://github.com/harnettd/huddle-landing-page](https://github.com/harnettd/huddle-landing-page)
- Live Site URL: [https://harnettd.github.io/huddle-landing-page/](https://harnettd.github.io/huddle-landing-page/)

## My process

### Built with

- HTML5
- CSS including Flexbox using the OOCSS methodology
- Sass

### What I learned

In completing this project, I learned how to

- use Sass on sass rather than scss files. Whereas scss files use semicolons to end statements
and curly braces to demarcate code blocks, sass files uses ends of lines and indentation instead.

- use Sass placeholder classes in conjunction with the `@extend` rule, i.e.,

```css
%img-block
    display: block
    height: auto

.img-logo
    @extend %img-block
    width: 26rem
```

- organize a sass file according the principles of OOCSS, in particular, separating structure 
from style.

### Continued development

I'd like to get better at putting together responsive webpages. For example, I'd like to make better use of
CSS properties like `min-width` and `max-width` rather than relying on a fixed `width`. 
Also, I'd like to learn more about how best to handle background images in responsive web design.

### Useful resources

- [The Basics of Object-Oriented CSS (OOCSS)](https://www.hongkiat.com/blog/basics-of-object-oriented-css/) - From this webpage, I learned the 
principles behind the OOCSS methodology. 
- [OOCSS + Sass = The Best Way to Write CSS](https://ianstormtaylor.com/oocss-plus-sass-is-the-best-way-to-css/) - This is an article discussing
how to use placeholder classes and the `@extend` rule in Sass.
- [Code Guide](https://codeguide.co/#css) - This is a CSS style-guide. In particular, it helped me decide how to order CSS declarations
within a block.
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - I got quite a bit better with Flexbox from 
reading through this webpage.

## Author

- Github - [Derek Harnett](https://github.com/harnettd)
- Frontend Mentor - [@harnettd](https://www.frontendmentor.io/profile/harnettd)

## Acknowledgements

- Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for posting this challenge.
