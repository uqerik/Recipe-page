# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](
  
). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- Mobile-first solution using CSS Grid and Flexbox

## The challenge
- This challenge will help you focus on writing semantic HTML. Ensure you think through what HTML elements are most appropriate for each piece of content. 

### Screenshot

![](./screenshot/recipe-page(mobile-view).png)
![](./screenshot/recipe-page(web-view).png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://uqerik.github.io/Recipe-page/#]

## My process

First i started by understanding the relationships between the various elements in the design and breaking it accordingly into parts. This helped get a clearer view on how to structure the html making styling a bit more concise.

When comparing the mobile view to the web view it was clear that the image had a margin in the web view therefore it was safer to place it in a separate <div> so as to be able to add margin when selecting it in media query without affecting other elements.

The preparation time section has its own <div> so it has own defined styling while ingredient, instructions and nutrition shared some styling since they have almost similar contents.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

i learned to target the bullets and numbers in list tag using css pseudo-element '::marker'. With this i changed the color of the bullet and numbers

Pseudo-element in CSS is like a “virtual element” that doesn’t exist in your HTML, but you can still style or create it with CSS.

It lets you style specific parts of an element (like the first letter, first line, before, after, or its marker) without needing to add extra HTML.

```css
.ingredients li::marker, .instructions li::marker{
  color: var(--Brown-800);
}
```

### Continued development

Been able to style CSS such that they can be reusable across my webpage by simply adding the class attribute.


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@uqerik](https://www.frontendmentor.io/profile/uqerik)
- Twitter - [@e_k0she](https://x.com/e_k0she)


