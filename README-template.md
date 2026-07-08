* [ ]

# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgment](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Live Site URL: [gavrilov-n.github.io/recipe-page.github.io](https://gavrilov-n.github.io/recipe-page.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS variables
- Flexbox
- CSS Grid

### What I learned

I have practiced CSS Grid as well as combined it with Flexbox. I also learned how to style ordered list and unordered list elements.

To see how you can add code snippets, see below:

```html
<div class="nutrition-table">
        <div class="table-row">
          <span class="label">Calories</span>
          <span class="value">277kcal</span>
        </div>
        <div class="table-row">
          <span class="label">Carbs</span>
          <span class="value">0g</span>
        </div>
        <div class="table-row">
          <span class="label">Protein</span>
          <span class="value">20g</span>
        </div>
        <div class="table-row">
          <span class="label">Fat</span>
          <span class="value">22g</span>
        </div>
      </div>
```

```css
.nutrition-table {
    font-family: 'Outfit', sans-serif;
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 42px;
}

.table-row {
    display: grid;
    border-bottom: 1px solid var(--stone-150);
    grid-template-columns: repeat(2, 1fr);
    justify-content: center;
}
```

### Continued development

I want to practice more with css grid. In particular I still have some difficulties structuring html and using css properties to align items on the grid, so I want to practice that area in particular.

### Useful resources

- [www.youtube.com/watch?v=rg7Fvvl3taU&amp;t=167s](https://www.youtube.com/watch?v=rg7Fvvl3taU&t=167s) - Good overview of css grid workflow
- [www.youtube.com/watch?v=JYfiaSKeYhE](https://www.youtube.com/watch?v=JYfiaSKeYhE) - Great introduction to css grid

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- [ ] I used Claude Code VScode plugin and Google Gemini
- [ ] I mainly used Claude Code for debugging, and asking Gemini for some css concepts.

## Author

- Website - [github.com/gavrilov-n](https://github.com/gavrilov-n)
- Frontend Mentor - [www.frontendmentor.io/profile/gavrilov-n](https://www.frontendmentor.io/profile/gavrilov-n)
- Twitter - [x.com/wakizasher](https://x.com/wakizasher)
