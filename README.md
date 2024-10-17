# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Full View](https://i.postimg.cc/J49ZMbzT/image.png)
![Windowed View](https://i.postimg.cc/1RdNrpw9/image.png)

### Link

- To be deployed soon.

## My process

### Built with

- Semantic HTML5 markup
- Bootstrap
- CSS custom properties
- CSS Grid
- Flexbox

### What I learned

Working on this project helped me understand the power and flexibility of **CSS Grid** for creating complex layouts. By combining CSS Grid and **Flexbox**, I was able to achieve the precise alignment of testimonial cards as shown in the design. CSS Grid allowed me to define the columns and control how each card should be positioned, while Flexbox helped with the alignment of elements within each card.

Here are some examples of what I learned:

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 20px;
}

.kira-card {
  grid-column: span 3;
  grid-row: span 2;
}
```

Using `grid-template-columns: repeat(12, 1fr);` allowed me to create a 12-column layout, making it easy to span elements across multiple columns for the desired visual effect. I also learned how to use `grid-row` to make elements span multiple rows.

### Continued development

In future projects, I would like to focus more on:

- **Responsive design**: Ensuring the layout adapts well to all screen sizes, especially smaller devices.
- **Advanced CSS Grid and Flexbox techniques**: To further improve my ability to create complex and visually appealing layouts.
- **Animation and transitions**: Adding subtle animations to improve user experience and make the design more interactive.

### Useful resources

- [CSS Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This is a comprehensive guide to CSS Grid and helped me better understand how to use grid properties effectively.
- [MDN Web Docs - CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - MDN's documentation was helpful for understanding the different grid properties and how they can be used together.

## Author

- Frontend Mentor - [@KevinG1000](https://www.frontendmentor.io/profile/KevinG1000)
- GitHub - [KevinG1000](https://github.com/KevinG1000)

## Acknowledgments

Thanks to the Frontend Mentor community for providing feedback and insights that helped me improve this project. Special thanks to the resources and guides that made understanding CSS Grid and Flexbox much easier.

