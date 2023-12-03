# Advanced CSS 

**Udemy Course:** Advanced CSS and Sass: Flexbox, Grid, Animations and More! 

**Teacher:** Jonas Schmedtmann

## Components

**Header**
- default CSS styling 
- box-sizing: border-box
- add font styling to the body 
- background image and gradient colours
- clip-path - adding a wedge (the slant to the bottom of the image)
- SEO optimisation with H1 / Span to styling within the inline element
- display: block 
- centering text-box
- entrance annimation using keyframes 
- animation timing function
- animated button with shadow effect

<img src="./screenshots/header.png" alt="Header" width="500px">

**About Section**
- use ``<main>`` and then add ``<section>``
- webkit background-clip for the ``<h2>`` text with a gradient and shadow. 
- transform to skew text on hove

Files located under /_typography.scss

**note:**
Need to add color: transparent, otherwise it won’t work. 

- Adding utlity classes to the utility folder, such as consistant margin bottom
- using &not:(last-child) to remove a style

<img src="./screenshots//not.png" alt="not CSS style" width="200">

- Learn More button with text-decoration on hover with a shadow

<img src="./screenshots//about.png" alt="About Section" with="500">




____

## SASS Script

* Folder: sass / main.scss
* package.json file, added a script to run compile sass

<img src="./screenshots/script-sass.png" alt="Sass Script" width="500">

* To run

``npm run compile:sass``

* This compiles into Folder: css / style.css 

**Note**
1. Add the -w to the end of the script to watch the file 
2. ``npm install live-server`` : reloads the site automatically (install globally on computer) 

___

## Practice 

1. 7-1 CSS Architecture

<img src="./screenshots/7-1.png" alt="7-1 CSS" width="200">

2. BEM - Block Element Modifier (Naming classes)

**BLOCK:** standalone component that is meaningful on its own

**ELEMENT:** part of a block that has no standalone meaning

**MODIFIER:** a different version of a block or an element




