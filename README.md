# Lesson Plan


### Overview
1. What we're going to do. Build a simple clone of instagram home page.

2. Learning Objectives
- HTML syntax
- CSS syntax
- CSS selectors + styles
- Basic Layout

3. Conceptual overview of what we're going to build. Everything in nested boxes and then columns are boxes stacked next to eachother.

![demo](materials/demo-analysis)

4. We'll Need three tabs open
- Codepen
- Full site example
- And site guide


**Solution**
https://codepen.io/tphdevdrop/pen/pWpVxW

### The demo
##### Step 0: style the `body` with background color

##### Step 1: Build the `<nav>`
- Build nav (white background w/ instagram  logo)

##### Step 2: Create a `<main>` container to center the content.
- margin: auto, max-width: 700px
- put light gray border to examine the effect
- put padding

##### Step 3: Build the `<header>`
- Get all the elements on the page
- `div.left-col`
- `div.right-col`
- style the columns
- use class selector for `<img>`
- use descendant selector to style `header button`
- for columns
  - display: flex
  - align-items: flex-end (allows us to vertically align)


##### Step 4: Build the `<article>`
- create `<p>` tag and c + p text content from course homepage

##### Step 4: Build the `<aside>`
- give the three divs a class of `.stats-column`
- display: flex;
- .stats-column --- width: 33%
- target `.stats-column strong` and give `color: black`

##### Step 4: Build the `<section>`
- get images from course page
- on `section`
  - `display: flex`
  - `flex-wrap: wrap`
  - `align-items: center` : *aligns items vertically*


- `section img`
  - `width: 31%` (to capture the border)

- on `section` we need to align horizontally
  - `justify-content: space-between`

##### Step 5: Build the `<footer>`
- `footer button` is 95% width, margin: 0;, padding-top: 15px
- `footer h6` has `text-align: center`
