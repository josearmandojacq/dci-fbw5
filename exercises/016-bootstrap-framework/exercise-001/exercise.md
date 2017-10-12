# Description

This is an exercise for the [Bootstrap Framework 3](https://getbootstrap.com/docs/3.3/). You'll need to figure out how to use different features and components of the framework.

# Tasks

1. Copy the folder **exercises/016-bootstrap-framework/exercise-001/template/** to your local exercise directory, that you use for development. This folder contains the needed code that is used to give you all needed tools as a template, including the SCSS version of Bootstrap.

1. Open a terminal, go to your newly created directory and run ```npm install``` once. Remember that you need to use 2 terminal windows / tabs to run the node-sass and live-server commands.

1. Create the following **navbar** and don't forget to change IDs to your own naming, as you should never copy code from the Bootstrap documentation without reading and modifying.:<br>![navbar](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/001-navbar.png)

1. Create the following **carousel**:<br>![carousel](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/002-carousel.png)

1. Create the following **jambotron**:<br>![jambotron](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/003-jambotron.png)

1. Create the following **blockquote**:<br>![blockquote](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/004-blockquote.png)

1. Create the following **grid with images**:<br>![blockquote](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/005-images.png)

1. Create the following **progress bars**:<br>![progress bars](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/006-progress.png)

1. Create the following **form**:<br>![form](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/007-form.png)

1. Create the following **dropup split button**:<br>![dropup](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/008-dropup-split.png)

1. Create the following **JS tab panel** with fade effect:<br>![tab panel](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/009-tab-panel.png)

1. Create the following **dismissable alerts**:<br>![dismissable alerts](https://github.com/noreading/dci-fbw5/raw/master/exercises/016-bootstrap-framework/exercise-001/images/010-dismissable-alerts.png)

# Needed tools

## SCSS compiler (node-sass)

How to run the SCSS compiler on your terminal:

```bash
# Change to the directory of your exercise
cd ~/Development/exercises/016-bootstrap-framework/

# Run it once
node-sass scss --output css

# Watch for file changes
node-sass --watch scss --output css
```

## Live server

```bash
# Change to the directory of your exercise
cd ~/Development/exercises/016-bootstrap-framework/

# Run the server, that reload automatically on change
live-server
```