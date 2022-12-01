# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](public/images/Four%20Card%20Feature%20SCreesnhot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)
- GitHub Repository - [Click Here](https://github.com/ColinMcArthur85/four-card-feature)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CUBE CSS Method
- SASS for building out CSS

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

That I can build a project much faster than expected. Usually I sit with these for almost a week but I did this in two nights of work. Maybe a total of 3-4 hours of work.

Ive also created a little 'cheat sheet' for creating a project now which has been helpful as Im creating my own process.

Also, Im quite proud of this use of data-types inside a media query

```scss
@media (min-width: 60rem) {
  .header {
    width: 40rem;
    margin-inline: auto;
  }
  .cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(4, 1fr);
    gap: $size-8;
    --flow-space: 0;
  }
  .card {
    &[data-type="supervisor"] {
      grid-column: 1 / span 1;
      grid-row: 2 / span 2;
    }
    &[data-type="team-builder"] {
      grid-column: 2 / span 1;
      grid-row: 1 / span 2;
    }
    &[data-type="karma"] {
      grid-column: 2 / span 1;
      grid-row: 3 / span 2;
    }
    &[data-type="calculator"] {
      grid-column: 3 / span 1;
      grid-row: 2 / span 2;
    }
  }
}
```

### Continued development

Not its time to build out a few of the 'premium' challenges. Ill give myself one more month of building thise out and then on to JavaScript. Wild how much Ive learned, essentially on my own.

## Author

- My GitHub - [Click Here](https://github.com/ColinMcArthur85)
- Frontend Mentor - [@ColinMcArthur85](https://www.frontendmentor.io/profile/ColinMcArthur85)
