# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](/images/screenshot.png)


### Links

- Solution URL: [Github](https://github.com/RaiIsNotYourGuy/profile-card-component-main)
- Live Site URL: [Github](https://raiisnotyourguy.github.io/profile-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

While overall this is fairly simple design (in the sense of the desktop and mobile design being the same), SVGs keep blowing my mind on how the work compared to traditional image formats. I also learned (mainly from just browsing r/webdev & r/web_design and snooping through youtube) more about behind-the-scenes components, like ::before & ::after, :root, and using comments to keep my code more organized than I have had it in the past. Links to my main influences for these in the resources section. Also, resetting CSS more to help make my layouts be less janky and more responsive.

```css
body {
  background-position: right calc(47vw + 15%) bottom calc(65vh - 15vw), left calc(40vw + 25%) top calc(72vh - 10vw);
}
```
^Credits to ApplePieGiraffe, what a strange way to keep things centered while the screen resizes.

### Continued development

Definitely on how SVGs work and more on code organization. 

### Useful resources

- [ApplePieGiraffe's solution to the background](https://www.frontendmentor.io/solutions/card-component-with-3d-animation-t0NqrfqMT) - Showed a solution to solving the issue with the background (being two SVGs and some color) centered and 
- [Kevin Powell - Before and After pseudo elements explained](https://www.youtube.com/watch?v=zGiirUiWslI) - Never learned about the before and after pseudo elements, was great to learn to be able to help create custom linebreaks without having to input a div. 
- [Speed Code Projects](https://www.youtube.com/watch?v=hFI2ye2_EI0) - Although this video shows more than what I used in my solution, it is definitely opened my eyes on how I can try to improve my code, whether it be with code organization, or learning how add smalls things (e.g. animations) to help improve a web page.

## Author

- Website - [RaiIsNotYourGuy](https://www.github.com/raiisnotyourguy)
- Frontend Mentor - [@raiisnotyourguy](https://www.frontendmentor.io/profile/raiisnotyourguy)
- Twitter - [@raiisnotyourguy](https://www.twitter.com/raiisnotyourguy)

## Acknowledgments

Thank you to the FrontendMentor Slack community for pointing me into the direction of ApplePieGiraffe's solution to the SVG backgrounds. And also thank you to ApplePieGiraffe for a crazy way to solve the issue of keeping the background fairly centered, I was searching for examples for about 2 hours with no breakthrough.