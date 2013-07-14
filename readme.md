GDI Core Web Accessibility
======================
This is the official Girl Develop It Web Accessibility curriculum. It was originally developed by Sylvia Richardson. This course is meant to be taught as a single two-hour workshop. There are three components: the course slides (classslides.html), a class activity handout (Kitten Alt text.docx), and an instructor guide (Instructor Guide.docx). 

These materials are under a Creative Commons Attribution-NonCommercial license (http://creativecommons.org/licenses/by-nc/3.0/deed.en_US).
## Suggested course description below

Who can use your websites? Are they accessible to as many people as possible?

Web accessibility is the process of making it easy for people with disabilities to use your sites.  Come to this workshop to learn more about designing with accessibility in mind—and building a better web experience for everyone.

This two-hour workshop will focus on general design principles, with some hands-on exercises. It is helpful to have some knowledge of HTML and CSS.  You should also plan to bring a laptop and some headphones to work along with the class.

## Theme customization

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});