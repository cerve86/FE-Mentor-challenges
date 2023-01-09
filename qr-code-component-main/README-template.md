# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./DesktopScreen.jpg)

See above the outcome of the challenge. Nothing major but good to learn on Flexbox positioning (made both the body and the container a flexBox) and some generic styling.

### Links

- Solution URL: [GitHub repo](https://github.com/cerve86/FE-Mentor-challenges/tree/main/qr-code-component-main/design)
- Live Site URL: [Solution site](https://fe-mentor-challenges.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Solution was pretty easy to implement rather more difficult to understand the right padding / sizing to match it to the design. Main learning for me was the utilization of Vercel to deploy the site. Pretty sure I made some mistakes but fun to have a webserver hosting so quickly. Now that I have connected  VSCode to Git to Vercel it works like a breeze ;) 

I've 'cleared' the CSS only with the margin and i've initialized some variables for the colors.

```css
*{
    --white: hsl(0, 0%, 100%);
    --lightgray: hsl(212, 45%, 89%);
    --grayishBlue: hsl(220, 15%, 55%);
    --darkBlue: hsl(218, 44%, 22%);
    margin: 0px;
}
```
Both body and .container are a Flex item:

```css
body {
  display: flex;
}

.container {
display: flex;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

## Author

- Frontend Mentor - [@cerve86](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@cerve86](https://www.twitter.com/cerve86)
