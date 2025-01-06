# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![](./images/screenshot_mobile.png)

![](./images/screenshot_desktop.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/kalpesh172000/qr-code-frontend-mentor-problem-1)
- Live Site URL: [Add live site URL here](https://kalpesh172000.github.io/qr-code-frontend-mentor-problem-1/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

1. How to keep a certain container/items fixed size when the screen gets too large but making it shrink when the screen gets smaller.
These inner items also decide the size of the div at the center. I haven't specified the width and height for the white div.
```css
.inner-items {
    max-width: 300px;
    width: 100%;
}
```

2. How to keep the items vertically center when parent container height is variable using flexbox and vh units.
```css
.body{
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
```

### Continued development

As the inner elements decide the size of the ceter div I had to decide the width of the inner elements by trial and error. I don't thing it is the optimam way to doing things. Is there any better way to do this without me having to think about width for each component in the div.

## Author

- Frontend Mentor - [@kalpesh172000](https://www.frontendmentor.io/profile/kalpesh172000)

