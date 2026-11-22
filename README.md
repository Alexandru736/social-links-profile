# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

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
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

For this project, I've encountered some little difficulties with making the whole pills clickable and focusable. I learned that when I use pseudo-classes, it's the same as if I'm inside that tag. 

I discovered that instead of using :focus-visible like:
```css
.link:hover, .link:focus-visible {
    .link {
        background-color: var(--green);
    }
    a {
        color: var(--grey-700);
    }
}
```
I can use it with :focus-within and make everything within the pill clickable and focusable with:
```css
.link:hover, .link:focus-within {
    background-color: var(--green);
    color: var(--grey-700);
}
```
In this process I put the class names inside the anchor tag and make it fill the whole available width

### Continued development

For this dificulty level, I'm very good with what I've learned so far. I'm just hoping to develop a keen eye to match mook designs perfectly.

### Useful resources

- [Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Media_queries/Using) - This helped me for understanding media queries principles
- [Focus Within Pseudo-Class](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:focus-within) - This documentation was useful for understanding the way to focus with the Tab key on the whole pill

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- What tools did you use (e.g., ChatGPT, Claude, GitHub Copilot)?
- How did you use them (e.g., debugging, generating boilerplate, brainstorming solutions)?
- What worked well? What didn't?

**Note: Delete this note and the content above if you didn't use AI, or replace with your own experience.**

I've used AI to evaluate comparisons between my work and the jpg files. I've also tried to ask it questions about how to make the pills clickable and hoverable. It is a bit of a shame that it doesn't really compare the pixels. Other than that, it's great tool for learning.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**
