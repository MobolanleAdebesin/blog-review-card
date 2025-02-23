# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop View]('./assets/images/Desktop View Frontend Mentor Blog preview card.png')

![Mobile View]('./assets/images/Mobile View Frontend Mentor Blog preview card.png')

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://blog-review-card-three.vercel.app/](https://blog-review-card-three.vercel.app/)

## My process

I started by mapping out each section of the component:

- card
- Category Tag
- Blog Illustration
- Card Title
- Card Description
- author's photo
- author's name

I added these elements to the page using a series of divs, an h1 tag, a p tag, img tags, etc.
I added a class to each element
I styled the component from top to bottom using the Figma design files for reference

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- I learned that I can use `object-fit` css property in order to adjust the dimensions of the blog preview image

```
.card-img.header{
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 1rem;
}

```

- I learned about how to resize font-sizes for different screens without using media queries. Instead, I used the `clamp` css function:

```
.card-description{
    font-family: Figtree-Medium;
    font-size: clamp(0.875rem, 3vw, 1rem);
    line-height: 150%;
    letter-spacing: 0;
    color: var(--gray-500);
}
```

### Continued development

I enjoyed exploring the Figma Designs for this project and I would like to improve my "Figma Literacy". Having a design system was helpful but some aspects, like how to apply the spacing, were confusing for me.

### Useful resources

- [Resource 1](https://css-tricks.com/almanac/properties/o/object-fit/) - This resource was helpful for learning more about the object-fit property
- [Resource 2](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit) - MDN is another resource I used for learning about the object-fit property
- [Resource 3](https://blog.dai.codes/responsive-css-without-media-queries/) - This article explained how to modify font-sizes without media queries

## Author

- Website - [Bola Adebesin](https://www.badebesin.com/)
- Frontend Mentor - [@MobolanleAdebesin](https://www.frontendmentor.io/profile/MobolanleAdebesin)
