# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

size of card es the same on desktop and mobile, because is small en desktop.

### Screenshot

![](./images/nft%20web.jpeg)

### Links

- Repository URL: [Add solution URL here](https://github.com/Alstarjet/nft-card-frontend-mentor)
- Live Site URL: [Add live site URL here](https://alstarjet.github.io/nft-card-frontend-mentor/)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned
I learned the usefull is add more that one class to my labels, because i had code repeat in css and is more readable if i have less.

```html
        <div class="data card_creator">
          <img src="./images/image-avatar.png" alt="">
          Creation of&nbsp<a href=""> Jules Wyvern</a> 
        </div>
```
```css
    .card_data{
      display: flex;
      width: 83%;
      justify-content: space-between;
      color:hsl(178, 100%, 50%);
    }
    .clock{
      color: hsl(215, 51%, 70%);
    }
    .data{
      display: flex;
      align-items: center;
    }
```


### Continued development
I see that i dnt know enough about html sematic and how to use the optios of grid and flexbox 


## Author

Frontend Mentor - https://www.frontendmentor.io/profile/Alstarjet
Twitter - https://www.linkedin.com/in/jose-alberto-estrella-767869a7/
