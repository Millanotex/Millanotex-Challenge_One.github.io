# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Desktop Design:

![Desktop design](https://user-images.githubusercontent.com/79281356/197018726-b0586583-38dd-4d6d-9a6c-216fd6515bb4.png)

Mobile Design:



![mobile design](https://user-images.githubusercontent.com/79281356/197018775-83f717ca-1d64-4346-8c8c-7750482d34f5.png)


### Links

- Live Site URL: [Add live site URL here](https://millanotex.github.io)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I decided to restart the challenge because I don´t feel comfortable with my first attempt, in this case, I use some of the tips I received, the use of the picture tag, for example, was much easier than using two IMG tags, i will continue doing the challenges to improve my skills


This was very useful

```html
   <picture class="perfume_card_pictures">
     <source
       media="(max-width:762px)"
       srcset="images/image-product-mobile.jpg"
       class="perfume_card_piture-mobile/>
     <img
       src="images/image-product-desktop.jpg"
       class="perfume_card_picture-desktop"
       alt="Gabrielle_Parfum"/>
   </picture>
```

### Useful resources

(https://getbootstrap.com/docs/5.0/layout/breakpoints/) - I used the breakpoints of bootstrap 5 to guide me .
(https://www.joshwcomeau.com/css/custom-css-reset/) -I used this to my problem to the views on the differents browser

## Author

[Daniel Millan](https://github.com/Millanotex)
[@DanielMillanR](https://www.frontendmentor.io/profile/DanielMillanR)




## Acknowledgments

Thanks to:
@correlucas and @vcarames for the tips

