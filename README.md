# simplified gulp.js

- [What is gulp](#what-is-gulp)
- [Requirements](#requirements)
- [How to install gulp?](#how-to-install-gulp)

## What is gulp

Gulp it's a free source toolkit for building JS-based applications. It processes and transfers files when building web pages.

## Requirements

- node.js
- npm

## How to install Gulp?

### node.js

1. Download the latest [node.js](https://nodejs.org/en/) features version of the zip file.
2. Run the setup to install the *node.js* on your computer
3. You need to set environment variables [tip: stackoverflow](https://stackoverflow.com/questions/27864040/fixing-npm-path-in-windows-8-and-10)
4. Open *cmd* and enter `node -v` command. It will display the installed Node.js version.
5. In *cmd* enter `npm -v` to display the version of installed npm (Node.js package manager).
6. In *cmd* enter the following command to install gulp `npm install gulp -g`. **-g** flag ensures that the gulp is installed globally and available for any project
7. To verify that gulp has been installed successfully enter the following command to display the gulp version `gulp -v`

### gulp

1. Download files from this repository and extract them in a new project folder
2. Open *cmd* and enter `npm install gulp`, files will be copied from global gulp
3. Gulp has various extensions defined at the top of the file, for example: `var sass = require('gulp-sass');` **IF** the console returns an `gulp-sass` *(name)* error type in google **gulp sass save-dev** *(dependence_name save-dev)*. On page [npmjs.com/package/gulp-sass](https://www.npmjs.com/package/gulp-sass) you will find information on how to install taht dependence (`npm install node-sass gulp-sass --save-dev`).

## Structure

- assets *(created by gulp)*
    - css
    - js
- dev
    - sass
    - js