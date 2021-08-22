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
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](Screenshot (46).png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

1) Make image responsive in Bootstrap using the "img-fluid" class.
```
<img src="" class="img-fluid" alt="">
```
2) background-size : cover -- makes the background image stretch/zoom to fill the background as necessary
   background-repeat: no-repeat -- normally the image will appear 2/3/4... times to cover the whole background but with no-repeat, the image 
   appears only once then the rest of the space gets filled with default/specified background color.

3) If you change the position to absolute, then the width and height of that element is still the same as it would be if it was static.
   If you use height: 50%, the height would be 50% of it's parent (as if position was static), and then due to absolute position it will re-        position itself. 

4) Use background image + linear gradient to achieve a image background with a layover color.

5) Be careful with linear gradient, as different browsers needs different css code for it to run (-webkit-, -moz- etc.).

Markdown guide - [The Markdown Guide](https://www.markdownguide.org/).

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
