
# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Chat app CSS illustration solution](#frontend-mentor---chat-app-css-illustration-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Screenshot

![](./images/Screenshot%20(227).png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I did my best on the ui design of the chat app and the two body background colors. I learned the use of flexbox to style the chat app properly.

```css
body::before{
    content: '';
    position: absolute;
    height: 730px;
    width: 475px;
    top: 0;
    left: -100px;
    background: var(--body-before-bg-gradient);
    border-bottom-right-radius: 400px;
    border-bottom-left-radius: 400px;
    z-index: -1;
}

body::after{
    content: '';
    position: absolute;
    height: 730px;
    width: 470px;
    bottom: 0;
    right: -125px;
    background-color: var(--body-after-bg);
    border-top-right-radius: 190px;
    border-top-left-radius: 250px;
    z-index: -1;
}
```

## Author

- Frontend Mentor - [@Trayshmhirk](https://www.frontendmentor.io/profile/Trayshmhirk)
- Twitter - [@TrayShmhirk01](https://www.twitter.com/TrayShmhirk01)

