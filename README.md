# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
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

![QR card component screenshot](./fmQR.png)

### Links

- Solution URL: [github](https://github.com/kchettiar1/fmQRcodeComponent)
- Live Site URL: [live site](https://fmqr.netlify.app/)

## My process

### Built with

- Semantic HTML5
- SCSS
- CSS Grid

### What I learned

- SASS partials
  Being able to split out my code in different files was an 'aha' moment.
  Keeping areas of code where I can easily locate for example typography styles, color styles, resets, layouts make troubleshooting easier and tidy.

- Using [SASS Functions](https://github.com/kchettiar1/fmQRcodeComponent/blob/main/src/sass/utils/_functions.scss) to handle relative size units.
  By including the above function I was able to pass px units:
  
```scss
  .card-text-heading {
    margin-block: u.rem(30);
    font-size: u.rem(20);
    font-weight: 700;
    margin-inline: u.rem(36);
    color: g.$dark-blue;
  }
```

### Continued development

I intend to work with a few more SASS projects to expand my knowledge in this area.

### Useful resources

- [Sass, BEM, & Responsive Design](https://youtu.be/jfMHA8SqUL4)
  A youtube tutorial by [Coder Coder](https://www.youtube.com/c/TheCoderCoder) taught me how to work with SASS partials. Additionally I learnt about SASS Functions, Helper and Utility classes.
- [Stop using an extension to compile Sass](https://youtu.be/o4cECvhrBo8)
  I used an NPM script to setup SASS thanks to this  Kevin Powell tutorial.
  
  I adapted the workflow to suit my needs and will aim to use this going forward for Static SASS sites.

## Author

- [Krishnan Chettiar](https://www.codingkc.com)
- [Frontend Mentor Profile](https://www.frontendmentor.io/kchettiar1/)
- [Twitter - @codingkc](https://www.twitter.com/codingKC)
