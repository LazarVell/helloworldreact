# helloworldreact

This is my first React app.

You can see the live version at : https://lazarvell.github.io/helloworldreact/

<b><h2>Objective</b></h2> - I wanted to get to know the basics of React. In adition to writing a simple hello world, I changed some of the React default settings. I made the logo spin faster and dyed it red. I also deployed a live version to GitHub using gh-pages.

<b><h2>How I did it</b></h2> - In adition to using the react library, I edited the package.json to be able to deploy the page to Gitbuh using gh-pages through the terminal. Otherwise a live version would not be present in this project.

The live deployment of the page was done using gh-pages, with the help of a guide posted here : https://github.com/gitname/react-gh-pages

For the sake of space, node modules folder was not updated, and the build is present in the gh-pages branch.

In adition to creating the simple "Hello World!", we did the following:

  Edited the package.json to add a homepage, as well as predeploy and deploy scripts to be run in order to deploy the page and have live access.

  The speed of the logo rotation is increased by 4x
  
  The color of the logo was changed!
  
    This was done using a CSS filter generator ( https://codepen.io/sosuke/pen/Pjoqqp ) to apply a color change directly to an SVG.
    
    The SVG was made to rotate faster through CSS transformation parameters.
    
  Added another element within the paragraph as a span (in React, a function that returns HTML elements will only return a highest parent element with it's children. If we wish to have 2 elements at the highest level, we must wrap them in another element that will act as a parent, otherwise we will not get the desired results from React.)

<b><h2>Greatest challenge</b></h2> - Deploying a React page had to be done in a completely different manner, compared to a regular webpage where I would just add, commit, push to GitHub and then activate a live version.

<b><h2>What I learned</b></h2> - React basics and deployment. I gained a better understanding of how React returns elements to populate the index page through it's functions and exports.
