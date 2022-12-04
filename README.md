# NFT-preview-card
Frontend Mentor NEWBIE FREE Challenge


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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![image](https://user-images.githubusercontent.com/119393713/205484468-3793517e-d02b-464e-b0e6-c67ac1465093.png)



### Links

- Solution URL: [https://github.com/TalasaDev/NFT-preview-card](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this challenge I learned how to insert an image and a background color within another <div> container that already contains an image, and how to style them to get a hover effect. The key concept to review is the position properties of an element.


`````HTML

<section class="main-image">
      <img src="./images/image-equilibrium.jpg" alt="image equilibrium">
      <div>
        <img src="./images/icon-view.svg" alt="icon view">
      </div>
</section>


`````CSS

container .main-image {
  position: relative;  
}

.container .main-image div {
  position: absolute;
  top: 0;
  background-color: hsl(178, 100%, 50%, 40%);
  width: 100%;
  height: calc(100% - 5px);
  z-index: 999;
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
  border-radius: 0.5rem;
}

.container .main-image div:hover {
  opacity: 1;
}

.container .main-image div img {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}


### Continued development

- Advanced CSS


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@talasa-dev](https://www.frontendmentor.io/profile/talasa-dev)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

