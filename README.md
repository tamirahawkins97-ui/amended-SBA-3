# amended-SBA-3

## Frontend Mentor - Maison Soleil Booking Dashboard solution

This is a solution to a design challenge on [Frontend Mentor](https://www.frontendmentor.io). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### Overview

#### The challenge

Users should be able to:
- View the optimal layout for the dashboard depending on their device's screen size
- See hover states for all interactive elements across the page
- Experience the 3D card fan hover interaction on the main booking cards

##### Screenshot

![](./preview.jpg)

---

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Flexbox
- 3D CSS Transforms & Perspective

### What I learned

In this challenge, I focused on implementing 3D transforms to create the layered "fanned" card effect and standardizing clean layout practices using CSS Grid and Flexbox.

```css
/* Perspective container and 3D card transformation */
.card-fan-container {
  perspective: 1000px;
}

.left-card {
  transform: rotateX(5deg) rotateY(-8deg) rotateZ(3deg) translateX(-100px);
}
