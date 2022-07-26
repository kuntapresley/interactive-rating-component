# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Screenshot


**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://github.com/kuntapresley/interactive-rating-component.git)
- Live Site URL: [Add live site URL here](https://kuntapresley.github.io/interactive-rating-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- desktop-first workflow


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

i learned mostly how to use css to manipulate the radio html elements,then how to use javascript to change the page 
<form class="Interactive__cta">
   <input type="radio" class="rating-btn" name="rating"id="rating1" value="1">
<label for="rating1">1</label>
<input type="radio"  class="rating-btn" name="rating"id="rating2" value="2">
<label for="rating2">2</label>
<input type="radio"  class="rating-btn" name="rating" id="rating3" value="3">
<label for="rating3">3</label>
<input type="radio"   class="rating-btn" name="rating" id="rating4" value="4">
<label for="rating4">4</label>
<input type="radio"  class="rating-btn" name="rating" id="rating5" value="5">
<label for="rating5">5</label>

  </form>
```
```css
input{

    display: none;
}
input[type=radio] + label{
    text-align: center;
    padding: 1rem;
    width:3rem;
    height: 3rem;
    border: none;
    cursor: pointer;
    border-radius: 50%;
        background-color: hsl(213deg, 19%, 21%) ;
    color: hsl(217, 12%, 63%);
    }
input[type=radio] + label:hover {
background-color: hsl(216, 12%, 54%) ;
color: hsl(0, 0%, 100%);
}  
    input[type=radio]:checked + label{
        text-align: center;
        padding: 1rem;
        width:3rem;
        height: 3rem;
        border: none;
        cursor: pointer;
        border-radius: 50%;
            background-color:  hsl(25, 97%, 53%) ;
        color: hsl(0, 0%, 100%);
         }
```
```js
submitBtn.addEventListener('click' ,() =>{
    thankYouSection.classList.remove('hidden');
    welcomeSection.classList.add('hidden');
});
```



**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

i will still like to develop my skills on responsive layout,and my javascript when it comes to figuring out what and when to target a particular event

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [slack](https://slack.com) - helped me in figuring out javascript and css to use

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [ifeanyipresley](https://www.your-site.com)
- Frontend Mentor - [@ifeanyipresley](https://www.frontendmentor.io/profile/ifeanyipresley)
- Twitter - [@legend_of_kunta](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments



**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
