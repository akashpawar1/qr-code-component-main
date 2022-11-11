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
- [Author](#author)


## Overview

### Screenshot

![Desktop screenshot](screenshot\desktop-view.jpeg)
![Mobile screenshot](screenshot\mobile-view.jpeg)

### Links

- Solution URL: [Github](https://github.com/akashpawar1/qr-code-component-main)
- Live Site URL: [Netlify](https://qr-frontend-mentor-by-akash.netlify.app/)

## My-process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned that to properly use transform translate function over entire page you have to make your parent element of a full screen size.

To see how you can add code snippets, see below:

```html
<main>
  <div class="qr-card">
    <img src="images\image-qr-code.png" alt="qr code image">
    <p class="qr-title">Improve your front-end skills by building projects</p>

    <p class="qr-text">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
</main>
```
```css
main {
  position: relative;
  height: 90vh
}
.qr-card {
   width: 270px;
   height: 450px;
   background-color: White;
   border-radius: 5%;
   position: absolute;
   top: 50%;
   left: 50%;
   transform: translate(-50%,-50%);
 }
```



### Continued development

I want to learn more about css position and responsive design.


### Useful resources

- [Geek for geeks](https://www.geeksforgeeks.org/4-different-ways-to-center-an-element-using-css/) - This helped me for making content in the center.


## Author

- Website - [Akash Pawar](https://akashpawar.netlify.app/)
- Frontend Mentor - [@akashpawar1](https://www.frontendmentor.io/profile/akashpawar1)
- Twitter - [@akashpawar00](https://www.twitter.com/akashpawar00)
