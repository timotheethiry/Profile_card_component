# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

- Build out the project to the designs provided

### Screenshot

![Desktop screen size] (./images/screenshot_desktop.png)
![Mobile screen size] (./images/screenshot_mobile.png)

### Links

- Solution URL: (https://timotheethiry.github.io/Profile_card_component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Sass

### What I learned

This project, simple yet instructive, was a good learning exercise.
I could use then recently discovered Sass, learn to draw a simple shape with CSS, practice the background layout and have a better grasp with absolute/relative positioning.

To see how you can add code snippets, see below:

```html
body {
  background: url(images/bg-pattern-top.svg), url(images/bg-pattern-bottom.svg), #19A1AD;
  background-position: -43% 54%, 133% -35%, 0 0;
  background-repeat: no-repeat;
  margin: 0;
  position: absolute;
  width: 100%;
  height: 100%;
  overflow: hidden;
}
@media screen and (max-width: 576px) {
  body {
    background-position: 170% 60%, -75% -60%, 0 0;
    background-size: 600px 600px;
  }
}
```
```css
.half-circle {
  width: 106px;
  height: 53px;
  border-top-left-radius: 54px;
  border-top-right-radius: 54px;
  position: absolute;
  top: -53px;
  left: 122px;
  background-color: #fff;
  box-shadow: 0 -1px 1px #19A1AD;
}
@media screen and (max-width: 576px) {
  .half-circle {
    left: 112px;
  }
}
```

### Continued development

In the future, I will search to improve my html structure and classes naming to keep my code maintenable. I'm interested in keep learning to draw shapes with CSS.
I'm not quite satisfied with how I positioned the background patterns, as it is not responsive. I focused on mobile (iPhone X) and desktop (14inches) viewports and need another solution to make the background responsive for al screen sizes.


### Useful resources

- [CSS shapes ressource 1](https://codepen.io/xram/pen/thLsk)
- [CSS shapes resource 2](https://stackoverflow.com/questions/22415651/half-circle-with-css-border-outline-only) - These two pages teached me an easy way to draw a half circle.

## Author

- Website - [Timothée Thiry] (https://timothee-thiry.welovedevs.com/)
- Frontend Mentor - (https://www.frontendmentor.io/profile/timotheethiry)

## Acknowledgments

I'd like to thank all the devs that spend time to help other devs through forums such as Stakoverflow, and those who share their code to use or learn from freely.

