# top-restaurant-page
The Odin Project Restaurant Page: Practicing DOM manipulation by dynamically rendering a simple restaurant homepage.

# Installation
npm install

# Assignment
1. Start the project the same way you began the webpack tutorial project.

* run `npm init` in your project directory to generate a `package.json file`.

*  run `npm install webpack webpack-cli --save-dev` to install webpack to the node_modules directory of your project.

* Quick tip: the `node_modules` folder can get really big. It is customary to add a `.gitignore` file to your project so that you don’t have to sync the contents of `node_modules` to github. The dependencies that are stored there can be installed from your package.json by running `npm install`, so you don’t need to sync them.

* Create a `src` and `dist` directory with the following contents:

* an `index.js` file in `src`

* an `index.html` file in `dist`. Go ahead and link the `main.js` file in a script tag. `main.js` is the file that will be generated by webpack.

* create a webpack.config.js file that looks just like our file from the tutorial.

2. Set up an HTML skeleton inside of `dist/index.html` with single `<div id="content">`.

3. Inside of `src/index.js` write a simple console.log or alert statement and then run `npx webpack`. Load up `dist/index.html` in a browser to make sure everything is working correctly.

* Quick tip #2: if you run `npx webpack --watch` you will not have to rerun webpack every time you make a change.

4. Create a bare-bones homepage for a restaurant. Include an image, headline, and some copy about how wonderful the restaurant is. It’s okay to hard-code these into the HTML for now just to see how they look on the page.

5. Now remove those elements from the HTML (so leave only the `html`, `body`, and `<div id="content">` tags) and instead create them by using JavaScript only, e.g. by appending each new element to `div#content` once the page is first loaded. Since we’re all set up to write our code in multiple files, let’s write this initial page-load function inside of its own module and then import and call it inside of `index.js`.

# Resources
https://www.theodinproject.com/lessons/node-path-javascript-restaurant-page
