# Frontend Mentor - QR Code Component Solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

---

## Overview

### Screenshot

![QR Code Component Screenshot](./screenshot.jpg)

### Links

- Live Site URL: [https://ed-wilson10.github.io/qr-code-component/](https://ed-wilson10.github.io/qr-code-component/)

---

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Working on this project helped me strengthen my understanding of CSS centering techniques and how to structure a clean, minimal card component. I practised using Flexbox to centre content both vertically and horizontally on the page, and used CSS custom properties to keep my styles consistent and easy to manage.

```html
<div class="card">
  <img src="./images/image-qr-code.png" alt="QR Code" class="qr-image" />
  <h1 class="card-title">Improve your front-end skills by building projects</h1>
  <p class="card-text">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</div>
```

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: hsl(212, 45%, 89%);
}
```

### Continued development

In future projects I want to continue improving my skills in:

- Responsive design across different screen sizes
- CSS animations and transitions
- Accessibility best practices (ARIA labels, contrast ratios)
- Moving towards component-based thinking with React

---

## Author

- GitHub - [@Ed-wilson10](https://github.com/Ed-wilson10)
- Frontend Mentor - [@Ed-wilson10](https://www.frontendmentor.io/profile/Ed-wilson10)
- X / Twitter - [@edsey_jr](https://www.twitter.com/edsey_jr)
