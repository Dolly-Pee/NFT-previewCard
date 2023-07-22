# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

The project helped was for me to majorly focus on css layouts.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![mobile-view-active](./images/Screenshot%202023-07-21%20at%2015-57-59%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)
![mobile-view](./images/Screenshot%202023-07-21%20at%2016-00-19%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)
![desktop-view](./images/Screenshot%202023-07-21%20at%2016-00-56%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I learnt how to show another element on an element whenever it is been hovered upon.

```css
.image__container{
    position: relative;
}
.image__container:hover .view-icon{
    display: flex;
}
.view-icon{
    background: hsla(178, 100%, 50%, .4);
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    display: none;
    cursor: pointer;
}
```

### Continued development

I want to focus on JavaScript and React js.


## Author

- Website - [Dolly-Pee]()
- Frontend Mentor - [@Dolly-Pee](https://www.frontendmentor.io/profile/Dolly-Pee)
- Twitter - [@precimyte](https://www.twitter.com/precimyte)



