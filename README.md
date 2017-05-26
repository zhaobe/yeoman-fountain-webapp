# yeoman-fountain-webapp
Yeoman generated fountain webapp

## Initial setup for this repo from scratch
- make sure you have a node version >= 6.0.0 and npm version >= 3.0.0 installed.
- `npm install --global yo` to install yeoman globally on local machine.
- `npm install --global gulp-cli bower generator-fountain-webapp` to install gulp-cli, bower, and the fountain webapp generator.
- `yo fountain-webapp` will guide you to the yeoman interface to create your webapp structure now.
- to debug `gulp serve` issue, ran the `npm outdated` command to check if there were missing packages.
- had to run `npm install` to install missing packages even though yeoman generated the template.

## Git cloning this repo
- git clone and run `npm install`, followed by `bower install`

## The configuration for this repo:
- Which JavaScript framework do you want? Angular 1
- Which module management do you want? Webpack with NPM
- Which JS preprocessor do you want? ES2015 today with Babel
- Which CSS preprocessor do you want? CSS
- Do you want a sample app? TodoMVC
- Would you like a router? Angular UI Router

## Running Things
- `gulp` runs all the gulpfile commands.
- you should be able to run `gulp serve` and it should run on a localhost, where you can open a browser to the specfied port.

## For testing
- `npm test` runs the unit tests based off karma and jasmine.
TODO: there's a failing test case currently.