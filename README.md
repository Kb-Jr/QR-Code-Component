# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



## Overview
This is a sample design for a QR-code component. It was built using HTML and CSS. It consists of two main parts which are the part that contain the QR image and the part that contains the accompanying text.


### Screenshot

![Desktop Screenshot](./screenshot_desktop.png)
![Mobile Screenshot](./screenshot_mobile.png)


### Links

- Solution URL: [https://github.com/Kb-Jr/QR-Code-Component.git]
- Live Site URL: [https://kb-jr.github.io/QR-Code-Component/]


## My process
The two main parts of this QR-code component were put in a wrapper. The wrapper assumed the role of a parent div while the two parts were the children. The display property of the parent div was given a value of "flex" and the flex-direction was assigned a value of "column" which made the child divs stack up vertically. Other layout properties such as the height, width, padding etc were tweaked to achieve the desired result. The colors used for this design were stored in variables which can be found at the beginning of the stylesheet (./styles.css).

The div which served as the container for the QR image part was assigned a background image with the value being the url for the required image. The background size was set to 100% 100% to ensure the width and height of the image covers the area of the div.

The border radius property was used to achieve the curved edges of the card (in white) and the image.

A single media query was used to set new rules for how the design should appear on the screen of a mobile phone.


### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow


### What I learned

I particularly learnt how to fetch google font types from using google apis. I also had the opportunity of using the viewport height (vh) units


## Author

- Frontend Mentor - [@Kb-Jr](https://www.frontendmentor.io/profile/Kb-Jr)
- Twitter - [@Joker__XL](https://www.twitter.com/Joker__XL)
