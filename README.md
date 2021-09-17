# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
### The challenge

- Build out the project to the designs provided by IMAGE

### Built with

- Semantic HTML5 markup
- SCSS
- CSS Grid
- Mobile-first workflow
### What I learned

- How to use background-position property in order to position images

CSS snippet:

```css
.container {
  background: hsl(185, 75%, 39%) ;
  background-image: url('../images/bg-pattern-top.svg'), url('../images/bg-pattern-bottom.svg');
  background-repeat: no-repeat, no-repeat;
  background-position: calc(-750px + (100vw - 375px)/2.3) calc(-600px + (100vw - 375px)/8), bottom calc(-600px + (100vw - 375px)/40) right calc(-750px + (100vw - 375px)/2.2);
}
```

### Link

[Project Link](https://profile-card-component-main-two-mauve.vercel.app/)  published on Vercel