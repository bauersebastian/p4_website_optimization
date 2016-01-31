## Website Performance Optimization portfolio project

To sucessfully view the optimized portfolio please visit [this site](http://pisada.de).

####Optimizations that I've done to the portfolio page (index.html)
- Separated the necessary css for printing the page from the main css file
- Minified all js and css resources
- Optimized all images in sizes and run them through ImageOptim
- Activated browser caching on the server side
- Acitvated gzip compression on the Nginx server
- Optimized loading of the Google Fonts
- Inlined critical css with the help of https://jonassebastianohlsson.com/criticalpathcssgenerator/

With the above mentioned optimizations the page gets 99/100 points for mobile and 99/100 points on Google Page Speed Insights.

####Optimizations on main.js for the pizza site:
- Moved calculations out of for loops in function changePizzaSizes and updatePositions
- Applied requestAnimationFrame for updatePositions
- Deleted determineDx function
- Replaced querySelector with getElementById and getElementsByClassName for better performance
- Saved pizzaElements.length to local variable for better performance on loop iterations
- Put the pizzasDiv variable out of the loop
- Created local variable for itemLength
- Declared the 'phase' and 'elem' variable outside the loop
- Only create the amount of moving pizzas necessary to fill the screen

####Optimizations on style.css for the pizza site:
- Added will-change declaration to the mover class

The goal was to achieve 60 fps while scrolling and reduce the load time when changing sizes of the pizzas.
