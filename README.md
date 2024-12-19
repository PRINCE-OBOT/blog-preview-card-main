# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
### Overview

### The challenge
I had challenges trying to use custom font, and understanding the purpose of font-weight in when creating custom font.

### [Screenshot](./assets/images/Screenshot.png)

### Links
- Solution URL : [Github Repository](https://github.com/PRINCE-OBOT/blog-preview-card-main.git)
- Live Site URL : [Live Project](https://prince-obot.github.io/blog-preview-card-main/)

### My process

Understanding how to match each element to the root pseudo class styling, was something I had to go through carefully.

### Built with
- Semantic HTML5 markup
- Flexbox for layout
- Media query

### What I learned

Ths project help me practice using custom fonts and root pseudo class.
```css
@font-face {
  font-family: Figtree;
  src: url(assets/fonts/static/Figtree-ExtraBold.ttf);
  font-weight: var(--fw-ExtraBold);
}
@font-face {
  font-family: Figtree;
  src: url(assets/fonts/Figtree-VariableFont_wght.ttf);
  font-weight: var(--fw-medium);
}

:root {
  --color-Yellow: hsl(47, 88%, 63%);
  --color-White: hsl(0, 0%, 100%);
  --color-500: hsl(0, 0%, 42%);
  --color-900: hsl(0, 0%, 7%);

  --fw-medium: 500;
  --fw-ExtraBold: 800;

  --fs-small : 0.875rem; 
  --fs-medium : 1rem;
  --fs-big : 1.5rem; 

  --color-black: #111111;
  --color-darkGrey: #6b6b6b;
}
```


### Continued development
I want to able to use root pseudo class more efficiently.

### Useful resources
ChatGPT 4o mini

### Author
- Twitter - [@obot_princ7790](https://www.twitter.com/@obot_princ7790)

### Acknowledgments
ChatGPT 4o mini has been a really great source for me to get detail information.

