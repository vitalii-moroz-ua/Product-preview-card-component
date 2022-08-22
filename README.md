# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](images/screenshot.png)

### Links

- Solution URL: [Product preview card component](https://github.com/vitalii-moroz-ua/Product-preview-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Custom image animation

### What I learned

I learnt to use ::after pseudo-element for image animation.

```css
.product-image::after {
  background-color: hsla(0, 0%, 100%, 0.3);
  color: var(--heading-dark);
  content: "Made with love";
  font-weight: 500;
  line-height: 1.6;
  opacity: 0;
  padding-bottom: 25rem;
  padding-top: 25rem;
  padding-left: 5rem;
  padding-right: 5rem;
  text-align: center;
  text-shadow: 0 0 5px hsl(0, 0%, 100%);
  text-transform: uppercase;
  transform: scale(2.3);
  transition: all 0.3s ease;
}

.product-image:hover::after {
  opacity: 1;
  transform: scale(1.2);
}
```

### Continued development

I'm planning on spending more time on mastering responsive design.

### Useful resources

- [css-tricks](https://css-tricks.com/stop-animations-during-window-resizing/) - This article helped me to stop animations during window resizing. It contains a really cool solution for the problem. I recommend you look into it.

## Author

- Frontend Mentor - [@vitalii-moroz-ua](https://www.frontendmentor.io/profile/vitalii-moroz-ua)
