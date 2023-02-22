# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

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
- Flexbox
- CSS Grid
- JavaScript - for mobile menu
- Mobile-first workflow


### What I learned

I have typically only used Flexbox in the past, but this time I knew I wanted to use CSS grid to layout the page correctly. 
Ultimately I found that using a combinatino of CSS grid and Flexbox gave me the most flexibility.

Based on feedback I received from the qr code project, I tried to only use classes in my HTML when they were truly needed to target a specific element instead of automatically adding a class to every element.

```html
 <main>
      <h1 class="title">The Bright Future of Web 3.0?</h1>
      <div class="content">
        <p>
          We dive into the next evolution of the web that claims to put the power of the platforms back into the hands of the people. 
          But is it really fulfilling its promise?
        </p>
        <button>Read More</button>
      </div>
    </main>
```
```css
body{
  grid-template-areas: 
            ". header header header ."
            ". image image sidebar ."
            ". content content sidebar ."
            ". article article article ."
  }
```


### Continued development

I want to continue focusing on condensing my CSS and keeping it as dry as possible. Sometimes I feel like I am tweaking the margins and padding areas too much. I want to expand my knowledge of CSS grid and to expand my use of custom style properties saved in the root at the top of the page.


### Useful resources

- [Kevin Powell's youtube channel](https://www.youtube.com/@KevinPowell) - I really like Kevin Powell's tutorials on CSS grid and flexbox. 


## Author

- Website - [Rachel Dooley](https://www.rachelandersondooley.com)
- Frontend Mentor - [@Rae1821](https://www.frontendmentor.io/profile/Rae1821)
- Twitter - [@RachelADooley](https://www.twitter.com/RachelADooley)




