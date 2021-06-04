# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Very Dark Magenta: hsl(300, 43%, 22%)
Soft Pink: hsl(333, 80%, 67%)

### Neutral

Dark Grayish Magenta: hsl(303, 10%, 53%)
Light Grayish Magenta: hsl(300, 24%, 96%)
White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Spartan](https://fonts.google.com/specimen/Spartan)
- Weights: 400, 500, 700

@media screen and (max-width: 700px) {
body {
overflow: scroll;
text-align: center;
}
.wrapper {
height: 160vh;
min-width: 0;
display: flex;
flex-direction: column;
justify-content: flex-start;
}
.top-section,
.bottom-section {
max-height: 550px;
max-width: 365px;
display: flex;
flex-direction: column;
}
.heading {
font-size: 40px;
}
.right {
height: 300px;
max-width: 370px;
text-align: center;
position: relative;
}
.right .review1 {
position: absolute;
left: 0;
right: 0;
}
.right img {
padding-left: 6px;
}
#review-text {
padding-left: 10px;
}
.right .review2 {
position: absolute;
left: 0;
right: 0;
}
.right .review3 {
position: absolute;
left: 0;
right: 0;
}
.bottom-section {
max-height: 700px;
display: flex;
flex-direction: column;
justify-content: space-around;
}
.box1 {
transform: translate(1px, 5px);
}
.box2 {
transform: translate(1px, 10px);
}
.box3 {
transform: translate(1px, 15px);
}
}
