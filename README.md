# Getting started

Hi EBFers :) Clone this repo, run `npm install` from within the folder to install all the build tools, then run `gulp watch` (presumably you have installed `gulp` with `npm install -g gulp`) to start the build pipeline. This will watch all changes to files in the `_js` and `_less` folders and recompile them to the `dist` folder. You _do not_ have to do this to work on the site. You can still edit the HTML files without adjusting the stylesheets/js files.

You can preview what you're doing in the browser by running `python -m SimpleHTTPServer` and heading to http://localhost:8000

# Folders starting with `_`

These folders are hidden from the public through Jeykll's build process (something Github uses to publish the pages), so we aren't exposing all the source for our dope stylesheets to the public.
