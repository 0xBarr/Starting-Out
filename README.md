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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Annotation%202023-07-09%20032213.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>

```
```css
.proud-of-this-css {
  color: papayawhip;
}
```css
.hov{
    width: 230px;
    height: 220px;
    position: relative;
    
}
.overlay{
    background-color: rgba(64, 224, 208, 0.705);
    position: absolute;
    height: inherit;
    top: 0;
    opacity: 0;
    width: inherit;
    border-radius: 5px;
}
.hov:hover .overlay{
    opacity: 0.7;
    cursor: pointer;
}
.view{
    position: absolute;
    top: 40%;
    left:40%



### Continued development

I want to practice two more HTML &CSS projects on Frontend Mentor,especially to practice display options(inline,absolute,relatve), and when to use them to help ease my work, before learning Javascript and then practicing more challenges.

### Useful resources

- [Example resource 1](https://www.tutorialspoint.com) - This helped me for the hover over image part. I really liked this pattern and will use it going forward.



## Author

- Frontend Mentor - [@0xbarr]
- Twitter - [@abdula6ix]


