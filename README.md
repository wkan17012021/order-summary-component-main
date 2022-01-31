# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This project builds on lessons learned from previous challenges in an attempt to replicate the template efficiently and accurately.

### The challenge

Users should be able to:

- See hover states for interactive elements

## My process

- Layout using main container and absolute positioning to centralise content.
- Use secondary child containers for the banner image, the text with nested div for the central template content.
- A lot of flexbox use!
- To limit media queries for responsive design, set widths/heights and max/min widths and heights on containers.
- Used additional image element tag for the background.
- For the interactive elements, used css :hover.

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- Better handle on absolute positioning this time round but still significant time was spent deliberating over the expected layout shift compared to the actual output so time was consumed adjusting padding, margin, widths etc.
- Use of flex helped abstract-away positioning of the smaller elements (icon, payment content, change link) both vertically and horizontally (in combination with margin: auto;).

### Continued development

The custom css is lengthy, definitely could be condensed as there is repitition of classes. SASS might help.

### Useful resources

- General google searches where I had forgotten css properties.
- Aadvik from Frontend Mentor: https://www.frontendmentor.io/solutions/nft-preview-card-component-solution-wRasehxIR#comment-61f661976d859468041ac43f

## Author

wkan17012021

## Acknowledgments

Aadvik1k (see above Useful resources)
