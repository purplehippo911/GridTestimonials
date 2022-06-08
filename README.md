# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Testimonials grid section solution](#frontend-mentor---testimonials-grid-section-solution)
  - [Table of contents](#table-of-contents)
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
  - [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot
Mobile
![mobile](design/finished-mobile-layout.png)

### Links

- Solution URL: [My solution](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7/hub/testimonials-grid-section-4ZweO4pMNY=)
- Live Site URL: [My live site URL](https://purplehippo911.github.io/GridTestimonials/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned
I learned how to use grid-template-areas and grid-area in real-life web development and I became a bit more comfortable with using Grid in my projects.

```html
       <div class="card card2">
        <div class="profile">
          <img src="images/image-jonathan.jpg" alt="Jonathan" />
          <div class="profile_info">
            <h3>Jonathan Walters</h3>
            <p class="bio">Verified Graduate</p>
          </div>
        </div>
        <div class="card_message">
          <h1 class="description">
            The team was very supportive and kept me motivated.
          </h1>
          <p class="info">
            “ I started as a total newbie with virtually no coding skills. I now
            work as a mobile engineer for a big company. This was one of the
            best investments I’ve made in myself. ”
          </p>
        </div>
      </div>
```
```css
.wrapper {
    max-width:80%;
    padding:5rem 1.6rem;
    padding-top:3rem;
    display:grid;
    gap:2rem;
    grid-template-areas: 
    "card1"
    "card2" 
    "card3"
    "card4"  
    "card5";
    place-self:center;
    justify-content:center;
    place-items:center;
}

```

### Continued development

I think I will continue with learning responsiveness with [Kevin Powell's][Responsive] 'Conquering Responsive Layouts'-course. And after that I think i should try to become more comfortable with Javascript and try to learn things like api's or Npm. 
[Responsive]:https://www.kevinpowell.co/courses/

### Useful resources

- [Wes Bos's Grid course](https://cssgrid.io/) - This helped me learn the fundamentals of Grid and also some tricks and tips.
  
- [A complete guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This is an amazing article which summarized the fundamentals of Grid and you can download their cheatsheet, which you can use when you forget how you do something in grid. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@purplehippo911](https://www.frontendmentor.io/profile/purplehippo911)
- Github - [@purplehippo911](https://github.com/purplehippo911)

## Acknowledgments


Thanks to [@mrLuisFer][1] and [@catherineisonline](https://github.com/catherineisonline) for their solutions which inspired me and helped me with my some of my grid for this challenge.

Don't forget to check out their solutions here:
  -[@mrLuisfer](https://github.com/mrLuisFer/testimonials-section/blob/main/docs/index.html)
-[@catherineisonline](https://github.com/catherineisonline/testimonials-grid-section-frontendmentor/blob/master/styles.css)

[1]:https://github.com/mrLuisfer                                    
