# Website Performance Optimization portfolio project

This project conaint same faile each file conatin same information,and this website run 
but performance of this website so bad and need to optimaze this website bay the same way.

## A way I used to optimaze website is:-

- minify html and css 
- inline css, write css in html
- used async to script tag
- compression image
- used media quere and print
- remove codes that not necsary
- removed google fonts link
- Resize images

Performance website before optimazation in mobile is (27) and desctop (28)
when optimazation accure performance in mobile is (92) and desctop (93).

## Optimazation include tow parts 

### Part 1: Optimize PageSpeed Insights 

- Minify CSS and JS files.
- Optimize images (size and compression)
- Eliminate render-blocking JavaScript and CSS in above-the-fold content:
  - style.css inlined in index.html.
  - Put the Google Analytics script to the footer of the page.

## Part 2: Optimize Frames per Second 

- Apply optimizations for PageSpeed: minify css and js, optimize images, inline css.
- Optimizations made in views/js/main.js:
  - Delete the function determineDx, since we change the pizza size inside the changePizzaSizes. Also optimize the loop in changePizzaSizes to put the new width in each .randomPizzaContainer.
  - Create all the variables outside of loops where possible.

### Udacity's instructions

You will optimize a provided website with a number of optimization- and performance-related issues so that it achieves a target PageSpeed score and runs at 60 frames per second.

1. Review our course on Website Performance Optimization using Google PageSpeed.
2. Download the required project assets.
3. Use Chrome Developer Tools to review the current state of various pages within the application and identify areas for improvement.
4. Review the code powering the website and identify areas where you believe modifications are warranted.
5. Iteratively make changes and test those changes using the tools available to you to determine if they are a performance gain or loss.


   
