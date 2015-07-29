## Overview

This is a simple contact list I have built using BackboneJS.

### Syntax


**Divshot protoype link**: http://development.tiy-backbonecontactlist.divshot.io

**Link to MongoDB API**: http://tiy-515.herokuapp.com/collections/kishan-contact/

**The following deserve thanks**:

Foundation.css, Backbone.js, jQuery, Underscore.js, MongoDB, HEROKU, and Sass.

## Usage

This template contains some simple `gulp` tasks. They are as follows:


- `gulp watch`: This will launch a Node Server and start the standard `watchlist` task
- `gulp bower`: This will move the bower components into their proper location. This will run during the `watch` task, but you may need to run it manually once in a while
- `gulp handlebars`: This will compile your handlebars (`.hbs`) files for you. Again, `watch` will watch for changes, but if you add new files, you'll need to run this or restart the `gulp watch` command.

There are many more tasks, and you really should read through the `gulpfile.js`, but the ones above will take care of you in most cases.
