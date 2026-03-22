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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the card depending on their device's screen size.
- See hover states for interactive elements (if applicable).
- Experience a fully accessible interface with semantic HTML.

### Screenshot

![Design preview](./design/screenshot.png)

### Links

- Solution URL: [https://github.com/dreamer111111/Frontend-Mentor-Stats-preview-card-component]
- Live Site URL: [https://stats-preview-card2.netlify.app/]

## My process

### Built with

- **Semantic HTML5** - Focus on accessibility and SEO.
- **CSS Custom Properties** - For efficient color and typography management.
- **CSS Logical Properties** - Using `inline-size` and `margin-block` for modern, internationalized spacing.
- **Flexbox & Grid** - For responsive layout control.
- **Mobile-first workflow** - Ensuring a seamless experience on small screens first.
- **Fluid Typography** - Utilizing `clamp()` for scalable font sizing.

### What I learned

During this project, I focused on implementing "Modern CSS" techniques. Specifically, I moved away from physical properties (left, right, width) in favor of **Logical Properties** to support different writing modes.

Example of logical spacing:

```css
.card-content {
  padding-block: 2.5rem; /* Replaces padding top and bottom */
  padding-inline: 2rem; /* Replaces padding left and right */
  text-align: start; /* Responsive to RTL/LTR languages */
}
```
