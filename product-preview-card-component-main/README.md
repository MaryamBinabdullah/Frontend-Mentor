# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

You'll find a screenshot of the finished project in 
- [desktop-screenshot](screenshot/Screenshot 2023-12-27 at 20-49-44 Frontend Mentor Product preview card component.png)
- [mobile-screenshot](screenshot/Screenshot 2023-12-27 at 20-50-06 Frontend Mentor Product preview card component.png)

both mobile and desktop are avalabile they might be a bit heavy as i didn't optimize them X_X 

### Built with

- HTML5 markup
- css3
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- desktop workflow

### What I learned

It was my first time putting my svg (the cart icon) in my css as i always happed to be adding it inline in my html 
or using fontawsome icons ^ ^ but I can't say much about my html as is only 30 lines of code but you could see the picture tag.

```css
.button[data-icon="trolley"]::before{
    content: "";
    background-image: url(images/icon-cart.svg);
    width: 15px;
    height: 16px;
}
```
## Author

- Name - [maryam]
- Frontend Mentor - [@code-inks]
- Find me on github [@code-inks]
- Telegram [@code_ink]