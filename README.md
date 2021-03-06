# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Finished product for web view](./images/finished-web-screenshot.png)

![Mobile top finished product](./images/mobile-top-finished.png)
![Mobile bottom finished product](./images/mobile-bottom-finished.png)

### Links

<!-- - Solution URL: [Add solution URL here](https://your-solution-url.com) -->

- Live Site URL: [https://achorn.github.io/stats-preview-card/](https://achorn.github.io/stats-preview-card/)

## My process

### Built with

- HTML5
- CSS
- Flexbox
- Web-first workflow

### What I learned

My plan for this project was to focus on the process. I took my time each step to plan my design and strategy for how I nested my html elements and then started from the outermost div and responsively designed inward.

My first attempt at designing the test and image containers was to have them evenly spit in the card component, then i scrapped that idea as it was a little to static for a responsive design.

Including the set up and this read me, this project clocked at around 4 hours.

hr 1: read through requirements, set up project repo, and set up html elements

hr2: style style style

hr3: small touch ups and fixing problems (img parent not wrapping img properly )

hr4: more cleaning up and finishing writeup

### Code I'm Proud of

Here is my media query that switches the image and test to a reverse columnthe the image sits on top of the text for mobile

```css
@media screen and (max-width: 1000px) {
  #card-container {
    max-width: 600px;
    text-align: center;
    width: 90%;
    flex-direction: column-reverse;
  }
  #text-container {
    padding: 20px;
  }
  img {
    object-fit: cover;
    width: 100%;
    height: 100%;
  }
}
```

### Continued development

Something I want to get better at is knowing what fonts to use for content and the write font sizing.

Also, I want to focus on media queries and whats considered too much or too little.

### Useful resources

- [FlexBox Complete Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This resource is always helpful when you forget some properties.

## Author

- Website - [Joshua Achorn](https://achorn.github.io/)
- Frontend Mentor - [@Achorn](https://www.frontendmentor.io/profile/Achorn)
- Twitter - [@achorn91338214](https://twitter.com/achorn91338214)

## Acknowledgments

Grace on Front End Mentor Slack channel who mentioned these styles to color an image properly

```css
parent-div {
  background-color: chosen color;
}
child-div {
  mix-blend-mode: multiply;
}
```
