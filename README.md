# Testimonials-Grid-Section

# Frontend Mentor - Testimonials grid section solution

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

- View the optimal layout for the site depending on their device's screen size

### Screenshots

![testimonial grid  Desktop SS](https://user-images.githubusercontent.com/110438720/185618747-9aae7034-155c-4e4b-942a-ac81dd526678.jpeg)
![testimonial grid SS Mobile](https://user-images.githubusercontent.com/110438720/185619585-4052df59-af94-460d-9ff1-15a5cefd991d.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This challenge was especially helpful in getting my hands dirty with html and css. One main aspect I wanted to learn was CSS grid and flex box and wrapping my head around how they work. Not only was I tasked to create a desktop version of the website but a mobile version as well. I learned about @media quarries and used the min-width property to establish when a mobile device would be used. 
The easiest workflow I found for CSS grid was to set up a grid-template-areas using the separate classes for each user in the order and span the design demanded.
```css
.container{
        grid-template-areas: 
        "user-001 user-001 user-002 user-005"
        "user-003 user-004 user-004 user-005"
        ;
    }
```
Then, all that needed to be done was to place the grid-area in each class in CSS
```css
    .user-001{
        grid-area: user-001;
    }
    .user-002{
        grid-area: user-002;
    }
    .user-003{
        grid-area: user-003;
    }
    .user-004{
        grid-area: user-004;
    }
    .user-005{
        grid-area: user-005;
    }
```
### Continued development

If I were to change anything about my code it would be a cleaner and reduced code both in HTML and CSS. Looking back through the code I could clean up my classes in HTML as well as implement some CSS custom properties for the colors so that it allows easy color theme adjustments in the future. I also feel as if I did some hacky adjustments in CSS to make the website look as close as possible to the design. In the future, I would like to look back at this project, review and either redo the project or adjust the code. 

As I go on I am going to continue getting more comfortable with CSS Grid and Flex box as these tools are vital in modern design. I would like to figure out how to use CSS Grid dynamically especially with clients needing to add more content to their website I would like to ensure that CSS Grid behaves predictably. 

### Useful resources

- [Example resource 1](https://www.example.com](https://www.youtube.com/watch?v=68O6eOGAGqA&t=584s&ab_channel=AngelaDelise) - This helped me with CSS Grid and is probably the easiest to understand. My only concern is this method seems static and as a beginner, I can not see how this can be used dynamically reason.

## Author

- Frontend Mentor - [@AvielDez](https://www.frontendmentor.io/profile/AvielDez)
