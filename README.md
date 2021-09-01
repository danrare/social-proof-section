# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
Designing a social proof section using visual guides.

### The challenge
 The challenge was to build a social proof section using any tools you like and getting it to look as close to the given design on mobile and desktop.

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![social-proof-design](images/social-proof-design-desktop.PNG)
![social-proof-design](images/social-proof-design-mobile.png)

The above are the screen shots of my design.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Building the social-proof-section was an interesting challenge. Firstly, I approached the design with mobile first work flow. For the mobile design I grouped the contents in to three divs, the top container, middle container and bottom container, all inside a container div. The first container housed the h1 and p tag, while the middle container housed the ratings and the bottom containers housed the testimonials. Although, I had to adjust the layout for larger screens, I did this by creating a sub container div and grouping my top container div and middle container div with another div named top. The design for mobile was very straight forward, just a few adjustments for the h1, p and the star image to get it to look as close to the design.

Secondly, I approached the design for larger screen sizes. It was quite challenging trying to get the layouts. For larger screen sizes I grouped the top and middle container with a div named top, this was so in order for me to implement the display flex property, then I gave it a value of role to make them appear side by sides, but I had to tweak the width of both divs using percentages to get my design close to the given design. The ratings inside the middle container was adjusted by setting the display property to absolute and the parent to relative, this enabled me to adjust the first and second rating effectively. Also, for the testimonial section I gave the parent div that is the bottom container a display of flex, with the value row to get each testimonial div to appear on the same line, I then used the position absolute property to position them as seen in the design.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- chrome developer tools

### What I learned

From this challenge I learnt how to make use of morethan one background images and more about responsive design. it was indeed fun.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
body{
    background-color: hsl(0, 0%, 100%);
    background-image: url("/images/bg-pattern-top-mobile.svg"),
    url("/images/bg-pattern-bottom-mobile.svg");
    background-repeat: no-repeat;
    background-position: top left, bottom right;
    background-size: 100%, 100%;
}
```
If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

I think I will like to focus on css arts and animations for now.

- [background-images](https://www.css-tricks.com/css-basics-using-multiple-backgrounds/) - This is an amazing article which helped me finally understand background-images. I'd recommend it to anyone still learning this concept.

## Author
- Frontend Mentor - [@Dan rare](https://www.frontendmentor.io/profile/Dan rare)
- Twitter - [@DanRare1](https://www.twitter.com/Dan Rare)

