# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned
At first i tried to add the qr image in the div but i run into the problem of the image overflowing the div and not respecting the border raduis. so instead i added the qr image as a background image in the div and that solved the problem.
```html
<div class="qrcode"></div>
```
```css
.qrcode {
    width: 90%;
    height: 300px;
    margin: 20px auto;
    border-radius: 12px;
    background-image: url(./images/image-qr-code.png);
    background-size: cover;
}
```

### Useful resources

https://www.w3schools.com/css/css3_object-fit.asp
https://stackoverflow.com/questions/587814/how-do-i-prevent-an-image-from-overflowing-a-rounded-corner-box
