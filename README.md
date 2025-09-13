# Frontend Mentor - Bento Grid Solution

![Bento Grid Preview](./preview.jpg)

This is my solution to the [Bento Grid challenge](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj) on Frontend Mentor. The challenge involved creating a responsive bento-style grid layout that works seamlessly across mobile and desktop devices.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- Experience a visually appealing bento grid with proper content organization
- See smooth transitions between mobile and desktop layouts

### Screenshot

**Mobile Layout:**

![Mobile Layout](./design/mobile-design.jpg)

**Desktop Layout:**

![Desktop Layout](./design/desktop-design.jpg)

### Links

- [Solution URL](https://github.com/your-username/bento-grid-solution)
- [Live Site URL](https://your-username.github.io/bento-grid-solution)

## My Process
Did the mobile version first before working on the desktop design which took awhile because i had not much knowledge of grids in css

### Built With

- Semantic HTML5 markup  
- CSS custom properties (variables)  
- CSS Grid for desktop layout  
- Flexbox for mobile layout and component styling  
- Mobile-first workflow  
- Custom font loading with `@font-face`  
- CSS media queries for responsive design  

### What I Learned

This project helped me deepen my understanding of **CSS Grid** and **responsive design patterns**. Key takeaways include:

**HTML Structure Example:**

```html
<div class="container">
  <div class="social">...</div>
  <div class="manage">...</div>
  <div class="maintain">...</div>
  <!-- ... more grid items -->
</div>
```

**CSS Grid Implementation:**

```css
.container {
  display: grid;
  grid-template-columns: 300px 250px 250px 300px;
  grid-template-rows: 400px 200px 280px;
  grid-template-areas:
    "create social social schedule"
    "write manage maintain schedule"
    "write faster grow   grow";
}
```

**CSS Custom Properties:**

```css
:root {
  --first-: hsl(254, 88%, 90%);
  --second-: hsl(256, 67%, 59%);
  --third-: hsl(31, 66%, 93%);
  --fourth-: hsl(39, 100%, 71%);
}
```

**Responsive Design Example:**

```css
@media (min-width: 1024px) {
  /* Desktop-specific styles */
  .container {
    /* Grid layout for desktop */
  }
}
```

### Continued Development
In future projects, I plan to focus on:
- Advanced CSS Grid techniques and complex layout patterns

### Author
- Frontend Mentor: @Noobeypro14
- GitHub: @Noobeypro14
