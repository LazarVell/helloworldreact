# helloworldreact

This is my first React app.

You can see the live version at : https://lazarvell.github.io/helloworldreact/

the live deployment of the page was done using gh-pages, with the help of a guide posted here : https://github.com/gitname/react-gh-pages

In adition to creating the simple "Hello World!", we did the following:

  Edited the package.json to add a homepage, as well as predeploy and deploy scripts to be run in order to deploy the page and have live access.

  The speed of the logo rotation is increased by 4x
  
  The color of the logo was changed!
  
    This was done using a CSS filter generator ( https://codepen.io/sosuke/pen/Pjoqqp ) to apply a color change directly to an SVG.
    
  Added another element within the paragraph as a span (in React, a function that returns HTML elements will only return a highest parent element with it's children. If we wish to have 2 elements at the highest level, we must wrap them in another element that will act as a parent, otherwise we will not get the desired results from React.)
    
By making this app, I learned how to directly apply color editing to an SVG through CSS filter property. I also gained a better understanding of how React returns elements to populate the index page through it's functions and exports.
