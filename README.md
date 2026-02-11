# GSAP Animation in Articulate Storyline

This project demonstrates basic GSAP animation integrated inside Articulate Storyline using JavaScript triggers.

## What I Learned

- Using gsap.from()
- Animating x and y axis
- Opacity transitions
- Understanding positive and negative values
- Triggering animation on click

## Sample Code

```javascript
var box = document.querySelector("[data-acc-text='box']");

gsap.from(box, {
  duration: 1.5,
  y: 200,
  opacity: 0,
  ease: "power3.out"
});
