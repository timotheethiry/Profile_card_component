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

![Desktop version] (./images/screenshot_desktop.png)
![Mobile version] (./images/screenshot_mobile.png)

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

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Timothée Thiry] (https://timothee-thiry.welovedevs.com/)
- Frontend Mentor - [@yourusername] (https://www.frontendmentor.io/profile/timotheethiry)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

