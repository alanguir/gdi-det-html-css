# CORE  HTML/CSS

This is Girl Develop It Detroit's Intro to HTML/CSS curriculum. It has been continually modified & improved by Cara Jo Miller, Nicole Rodriguez, Laura Eagin, and Leeann Drees. 

This curriculum is a modification of the original Girl Develop It Core HTML/CSS curriculum, which was created through the contributions of Pamela Fox, Alexis Goldstein, Erin M. Kidwell, Izzy Johnston, and Jen Myers.

The course is meant to be taught in 2 four-hour sections. 

## Classes

### Session 1 (session1.html)

	- What is HTML?
	- Anatomy of a Website
	- Folder Structure
	- Anatomy of an HTML Element
	- Doctype + Head & Body Tags
	- Nesting
	- Elements: Paragraphs, Headings, Formatted Text, Links, Images, Line Breaks, Ordered & Unordered Lists, Tables
	- Comments

	- What is CSS? 
	- CSS Syntax
	- Selectors: Elements, Child
	- Properties: Color, Background-color, Font-family, Font-size
	- Where to find fonts & colors
	- Linking CSS to HTML
	- Cascading

During Session 1, students create a simple HTML page and add minimal styling toward the end.

Homework assignment: viewing source code & inspecting elements on favorite websites, + setting up for Session 2.


### Session 2 (session2.html)

	- Review
	- HTML5 Structural Elements: header, main, aside, footer
	- Inline vs. Block Elements
	- Box Model
	- CSS Properties: width, height, 
	- Divs & Spans
	- IDs & Classes
	- Positioning: static, relative, absolute, & fixed
	- Floats & clearing
	- Z-index
	- Psuedo-classes
	- How does a website work? (Domain & hosting)
	- What's next?

During Session 2, students create a new HTML page with more advanced styling & a simple layout.



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
```
