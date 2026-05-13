# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/Frontend%20Mentor%20-%20Four%20card%20feature%20section.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/four-card-feature-solution-ywOOqpIkjR)
- Live Site URL: [Add live site URL here](https://four-card-feature-delta-tawny.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned to use the element before to make the color lining on top of the cards.

```css
.box::before,
.box2::before,
.box3::before,
.box4::before {
  content: "";
  position: absolute;
  top: -0.25em;
  left: 0;
  right: 0;
  height: 1em;
  border-radius: 0.5em 0.5em 0 0;
  z-index: -1;
}
```

### Continued development

For continued development I have no comment right now, I think the page is what was ment to be.

### AI Collaboration

I used Claude AI for learning by asking what options did I had when trying to solve every problem I faced.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Raley17)
