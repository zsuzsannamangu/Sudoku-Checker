# _Sudoku Checker_

#### _Sudoku is a game where players must fill in a 9 x 9 board with the numbers 1 through 9, {06/11/2019}_

#### By _**{Zsuzsanna Mangu}**_

## Description

_{This application checks if a completed Sudoku puzzle is “legal.” In other words, it ensures that each row, each column and each 3x3 grid contain all numbers from 1 to 9 with no repeats.}_

## Setup/Installation Requirements

* _Install Node.js and its corresponding package manager (npm) from Node's website_
* _Confirm that Node and npm are in place by checking the versions - run $ node -v then $ npm -v_
* _Clone the repository_
* _Navigate to root directory_
* _Install all required packages locally by running $ npm install in the command line_
* _Run $ npm run build to bundle code_
* _To check the application in the browser run $ npm run start_

## Configuration/dependencies

  * _webpack_ - Webpack is a module bundler that runs by loading assets such as plugins
  * _webpack-cli_ - this package allows us to use Webpack from the command line
  * _webpack-dev-server_ - to set up a live development server so our our code automatically rebundled and reloaded
  * _eslint and eslint loader_ - to check for errors and typos (we need the loader as well to use the linter with Webpack)
  * _uglifyjs-webpack-plugin_ - to minify our code to the bare minimum so our page loads faster
  * _clean-webpack-plugin_ - to clean up our dist folder as it's getting cluttered
  * _css-loader and style-loader - to transform our CSS into JavaScript code so Webpack can bundle it
  * _jquery, popper.js and bootstrap_- to develop the front end of our application
  * _html-webpack-plugin_ - to use Webpack to generate HTML files
  * _jasmine-core and Jasmine_ - Jasmine is a JavaScript testing framework to write tests
  * _Karma_ - to run tests wrote with Jasmine
  * _Babel_ - to fit all browsers, we compile code from ES6 to older versions with Babel

## Specs

  * Each row contains all numbers from 1 to 9 with no repeats.
  * Each column contains all numbers from 1 to 9 with no repeats.
  * Each of the nine 3 x 3 grids contain all numbers from 1 to 9 with no repeats.

## Limitations

_{This is only a sudoku checker, it does not allow users to create a sudoku puzzle.}_

## Support and contact details

_{Feel free to contact me at zsuzsannamangu@gmail.com with any questions.}_

## Technologies Used

_{Javascript, webpack, Jasmine and Karma for testing}_

### License

*{MIT}*

Copyright (c) 2019 **_{Zsuzsanna Mangu}_**
