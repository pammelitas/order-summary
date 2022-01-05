

# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://github.com/pammelitas/order-summary.git)
- Live Site URL: [Add live site URL here](https://pammelitas.github.io/order-summary/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I'm learning how to correctly position elements around the site, using the flex property, for example, and correctly grouping and nesting the elements in divs to keep my design and code more organized.


```html
<div class="annual-plan">
      <img class="icon-music" src="images/icon-music.svg" alt="icon-music">
      <h3>Annual Plan</h3>
      <p>$59.99/year</p>
      <div class="card-changeprice">
        <p>Change</p>
      </div>
    </div>
```
```css
.card-payment{
    background-color: #3829e0;
    width: 80%;
    height: 45px;
    color: white;
    border-radius: 10px;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 25px;
    margin-top: 25px;
    font-size: 14px;
    font-weight: 700;
    -webkit-box-shadow: 10px 10px 20px rgba(56, 41, 224, 0.15), 15px 15px 30px rgba(56, 41, 224, 0.15);
          box-shadow: 10px 10px 20px rgba(56, 41, 224, 0.15), 15px 15px 30px rgba(56, 41, 224, 0.15);
}
```

### Continued development

I would love to continue working and experimenting with flexbox as well as using css grids and bootstrap, as well to keep practicing positioning with css!


### Useful resources

- [Resource](https://stackoverflow.com/questions/56998624/html-css-align-text-in-center-of-rectangle) - This question on Stack Overflow helped me and saved me so much time and headache! I had written the correct properties ''justify-content'' and ''align-items'' as well, but I didn't place the flex display needed for those properties to work.

* This piece of code is at the top, on ### What I learned on .card-payment CSS. *


## Author

- Github - [pammelitas](https://github.com/pammelitas/)
- Frontend Mentor - [@pammelitas](https://www.frontendmentor.io/profile/pammelitas)
- Instagram - [pammelitas](https://instagram.com/pammelitas)
