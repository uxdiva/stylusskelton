# Stylus Skeleton

This project is the base setup for CSS styles for any site. I've taken the useful (opinionated) parts from (https://necolas.github.io/normalize.css/ "Normalize.css"), broken them into smaller modules and added base styling for items like responsive typography. This was done to
* create a more module system for managing styles
* combine Normalize recommendations with my base styles.

This is all still very much in the works, but provides a clean start for most projects. And the structure makes it very easy to change and update properties such as font-face and color.

## Gulp Companion
Check out my (https://github.com/uxdiva/gulpskeleton "Gulp Skeleton")  project. And this project into the `src/stylus` folder to be all set to go with a nice development workflow.

### More Styles in Gulp Structure
The file structure I have for the gulp workflow allows for giving styling to layouts/pages/parts within the layouts folder. In other words, styles that are global, like color, form fields, typography, should exist with in the `base` folder. But styles that are particular to a template, page, or module, should be in the layouts folder.

You will need to uncomment the line in `styles.styl` to allow that file to read any styles placed in the layouts folder.
