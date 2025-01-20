# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![screenshot](./images/Capture-2025-01-20-174330.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- Center something vertically

I use flex layout to make it, but it doesn't work. I realized that's because **I don't give my container a height**, this is the reason.

```css
.container {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
```

- give pic a border-radius

I wrapped the img with a div(card__img), and give card__img a border-radius, but it didn't work. After searching I found out that I also need to add `overflow:hidden` to **hide the part of the img covered by the rounded corners**

- seeing is not believing

must make pic in PS or use figma. I tried to use my screenshot tools to measure and finally get a wrong result.

### Continued development

Figma says that the card has a 40px padding at the bottom, but I don't find this useful. I'd like to know if it's necessary to implement this part and if it's useful.

### Useful resources

Just gpt.
