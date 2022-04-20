# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](https://github.com/Just9krish/FAQ-accordion-card-main/blob/330a06669f8a0b4acb884ae55804573a566fca41/design/desktop-design.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

```css
.accordion-content {
    font-size: 0.75rem;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.4s;
}

.accordion input:checked~.accordion-content {
    max-height: 100%;
}

.accordion input:checked~label::after {
    content: url("images/icon-arrow-down.svg");
    height: 100%;
    transform: rotate(180deg);
}
```

### Continued development

I will keep learning these simple trick of css in future and my focus on js.

## Author

- Linkedin - [@rvamit2648](https://linkedin.com/in/amit-vishwakarma-bb54b222a)
- Instagram - [@Just9krish](https://www.instagram.com/just9krish/)
- Frontend Mentor - [@Just9krish](https://www.frontendmentor.io/profile/Just9krish)