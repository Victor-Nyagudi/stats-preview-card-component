# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
 
## Overview

### The challenge

The challenge is to build out this card component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

The designs are in JPG static format. Using JPGs will mean that you'll need to use your best judgment for styles such as `font-size`, `padding` and `margin`. 

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./dist/screenshots/stats-preview-card-component-fullscreen.png)

I've included 4 screenshots in the `/screenshots` folder: mobile, tablet, desktop, and fullscreen.

### Links

[- Solution URL](https://www.frontendmentor.io/solutions/mobilefirst-solution-using-bem-naming-convention-and-flexbox-jkG0sHcID)
[- Live Site URL](https://victor-nyagudi.github.io/stats-preview-card-component/)

## My process

I started with the HTML alone then did the CSS for the mobile version. This process is easier, that way I'm not 
overwriting too many things in media queries. 

Had a little trouble with margins and padding on this one, especially centering the card itself, but I figured
it out eventually.

The image used in the design had a purple filter applied, but the one in `/images` folder was black and white.

After submitting my solution and asking a question, some really helpful people popped into the comments and 
introduced me to the `background-blend-mode` CSS property which can be used to blend the background color with a 
background image.

I used this along with a few changes in the `filter` property to arrive at the final color. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how you can change the filter on images using the `filter` property. I also read up quite a bit
on background images and flexbox. 

I used `flex-flow: row-reverse;` to change the order of the items - something I haven't used much until now - so I guess I can include that in things I learned.

This is the first time I've heard of and used `background-blend-mode`. It made life much easier for me, and I'm
glad I learned about it. 

Found this very [helpful article](https://css-tricks.com/almanac/properties/b/background-blend-mode/) that explained it clearly and concisely.

### Continued development

I still need to work on time management. I completed this one a little bit faster, but I can do better. Again,
more practice should help with this. 

I also need to practice working with images more. I'm not struggling with it, but it's not second nature just yet.
Same goes for flexbox. 

One step at a time. 