# Frontend Mentor - QR code component

![Design preview for the QR code component coding challenge](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Screenshot of desktop solution](/images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/funficient/fem-qr-code)
- Live Site URL: [Add live site URL here](https://funficient.github.io/fem-qr-code/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

There are many different ways to center a div. I always struggle with this! I learned that to center the center card the body has to have the flexbox center align properties set, not the card itself.

```html
<body>
  <div class="card">
    <img src="images/image-qr-code.png" alt="" />

    <div class="text-container">...</div>
  </div>
</body>
```

```css
body {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.card {
  background-color: var(--color-white);
  border-radius: 20px;
  display: flex;
  flex-direction: column;
  text-align: center;
  max-width: 20rem;
  padding: 1rem;
  margin: auto;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
}
```

### Useful resources

- [Standard css reset](https://piccalil.li/blog/a-modern-css-reset/) - Setting up the CSS correctly avoids a lot of problems later on.
- [Markdown guide](https://www.markdownguide.org/cheat-sheet) - Being new to markdown, I need a reference sheet to know how to correctly display everything in the readme file.

## Author

- Website - [Kate Dames](https://www.funficient.com)
- Frontend Mentor - [@funficient](https://www.frontendmentor.io/profile/funficient)
- Twitter - [@funficient](https://www.twitter.com/funficient)

## Acknowledgments

A big thank you to the awesome projects on FrontEnd Mentor! It really is the best way to learn!

A special shoutout to @fidellim and @correlucas for their very helpful feedback to improve my project.
