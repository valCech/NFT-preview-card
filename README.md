# NFT-preview-card
Etherium NFT preview card
# NFT-preview-card-component

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot



Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

HTML, CSS
Flex, inline-block



### What I learned - OVERLAY!
The z-index CSS property sets the z-order of a positioned element and its descendants or flex items. Overlapping elements with a larger z-index cover those with a smaller one.
I had a hard time to overlay images, to make one appear on a top of each other.
I have also learnt about using var in css

See code snippets EXAMPLE below:

<div class="hero_img">
   <img src="./images/image-equilibrium.jpg" alt="Equilibrium, a multicolor cube" />
   <div class="overlay">
      <img src="./images/icon-view.svg" alt="">
   </div>
</div>

..overlay {
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  z-index: 1;
  background-color: hsla(178deg, 100%, 50%, 0.5);
  opacity: 0;
  display: grid;
  place-content: center;
  transition: opacity 200ms ease-in-out;
}
.overlay img {
  width: 3rem;
  height: 2rem;
}
.overlay:hover {
  opacity: 1;
}

Screenshot:
<img width="337" alt="Screenshot 2022-08-08 at 09 21 55" src="https://user-images.githubusercontent.com/102651272/183373251-9228802a-d246-497c-8793-fa0905f636ab.png">



### Continued development

I think its time to start some project w JS in it


### Useful resources


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@valCech](https://www.frontendmentor.io/profile/valCech)
- LinkedIn - https://www.linkedin.com/in/vlastimil-šlechta-2988b3104/



## Acknowledgments
Thanks to the Front End Mentor community for advice

