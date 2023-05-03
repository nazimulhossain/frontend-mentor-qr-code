# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

- Desktop Screenshoot :

![](./desktop-screen.png)

- Mobile Screenshoot:

![](./mobile-screen.png)

### Links

- Solution URL: (https://your-solution-url.com)
- Live Site URL: (https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

For centering the qr box inside the container I used absolute positioning by making body as position realtive.

To see how you can add code snippets, see below:

```css
body {
  font-family: 'Outfit', sans-serif;
  height: 100vh;
  position: relative;
  background-color: hsl(212, 45%, 89%);
}

.qr-box {
  width: 350px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 24px;
  background-color: hsl(0, 0%, 100%);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.4);
  border-radius: 15px;
  padding: 16px;
  text-align: center;
}
```
