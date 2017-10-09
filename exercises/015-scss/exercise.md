# Description

This is an exercise for SCSS. You'll need to remember how to use imports, nested rules, etc.

How to run the SCSS compiler on your terminal:

```bash
# Change to the directory of your exercise
cd ~/Development/exercises/015-scss/

# Run it once
node-sass scss --output css

# Watch for file changes
node-sass --watch scss --output css
```

# Tasks

* Use the code of **exercise-014** in the **/exercises/014-media-queries/result** folder and copy it to a new local folder for your exercise.

* Create a new directory "scss"

* Rewrite the CSS to SCSS using the features that make your life easier (like variables, nested rules, etc.).

* Seperate the CSS code into multiple files (like "_variables.scss", "_buttons.scss", "_grid.scss", etc.).

* Write a mixin for "border-radius" that generates the following code, with a variable radius value:
```
-webkit-border-radius: 10px;
-moz-border-radius: 10px;
border-radius: 10px;
```
