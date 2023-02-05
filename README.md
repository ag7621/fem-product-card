# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![Desktop preview image for Profile card component challenge](/images/desktop-preview.png "Desktop preview")
![Mobile preview image for Profile card component challenge](/images/mobile-preview.png "Mobile preview")

### Links

- Solution URL: [Solution](https://github.com/ag7621/fem-profile-card)
- Live Site URL: [Live Site](https://ag7621.github.io/fem-profile-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

In this challenge I decided to try and use css selectors to target similarly styled html rather than use classes in efforts to reduce the clutter of having a class on every component. For the size of this project I think it worked out reasonably well, but I imagine in future, larger sized projects that it wouldn't be an ideal solution.

```html
<article class="card">
  <div class="card__bg">
    <img src="images/bg-pattern-card.svg" alt="">
    <div class="card__avatar">
      <img src="images/image-victor.jpg" alt="">
    </div>
  </div>
  <div class="card__body">
    <h1>Victor Crest <span class="age">26</span></h1>
    <p>London</p>
  </div>
  <div class="card__info">
    <div>
      <h2>80K</h2>
      <p>Followers</p>
    </div>
    <div>
      <h2>803K</h2>
      <p>Likes</p>
    </div>
    <div>
      <h2>1.4K</h2>
      <p>Photos</p>
    </div>
  </div>
</article>
```

Positioning multiple background images was something I had not done previously either and was a nice mini challenge learning how to do it. Although my solution is not pixel perfect at the mobile scale, it is at least responsive. I will continue to investigate better solutions to this.

### Continued development

Although I used I tried to use minimal classes to declutter the html for readability I'm not confident that it worked out better than if I had just used classes on needed components. In a larger scale setting I think it would make it more difficult to manage the code with a selector mass controlling styling, but at the time I felt like spamming utility classes was too much. This is something I would like to continue researchin for ideal solutions.

In attempts to create pixel perfect styling, I feel like I used a lot of tiny, perhaps unneeded adjustments to the css code. While I am content with how it turned out, it feels like too much micro managing and I imagine there is a better solution out there for me to learn. 

I ran into an issue at the start where I had set a css variable for font-size using REM on the body, and found everything to be too oversized. It took me some time to realize that the true font size was much higher than I had thought I set it at. Eventually I resolved it with lowering the variable REM until it had matched the style guide, but don't feel this was ideal either. This is also something I need to look into further.

Overall, despite being a relatively simple design I feel like I overthought way too much of it, and should have allowed the responsiveness to do the work vs managing every tiny bit of the project. I did enjoy the learning experience much though, and will take these findings into future project setup considerations.

### Useful resources

- [BEM cheat sheet](https://9elements.com/bem-cheat-sheet/) - This helped me understand the basics of how BEM looks and how to name classes.
- [Kevin Powell Youtube](https://www.youtube.com/@KevinPowell) - Amazing channel by veteran web developer Kevin Powell which helped me to understand CSS much better.
- [Josh W Comeau CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - A CSS reset referred to in a video by Kevin Powell.

## Author

- Frontend Mentor - [@ag7621](https://www.frontendmentor.io/profile/ag7621)
