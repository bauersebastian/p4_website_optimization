## Website Performance Optimization portfolio project

To sucessfully view the optimized portfolio please visit [this site](http://pisada.de).

####Optimizations that I've done to the portfolio page (index.html)
- Separated the necessary css for printing the page from the main css file
- Minified all js and css resources
- Optimized all images in sizes and run them through ImageOptim
- Activated browser caching on the server side
- Acitvated gzip compression on the Nginx server
- Optimized loading of the Google Fonts

####Optimizations on main.js for the pizza site:
- Moved calculations out of for loops in function changePizzaSizes and updatePositions
- Applied requestAnimationFrame for updatePositions
- Deleted determineDx function

