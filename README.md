#grunt demo

from: http://teamtreehouse.com/library/up-and-running-with-grunt

- requires node, best to install node w/ homebrew to avoid sudo issues (not sure how node is currently installed)
- run commands from project folder:
- npm init
    - sets up package.json file
- npm install grunt --save-dev
    - installs grunt, adds to package.json file
- install modules and configure gruntfile.js (see gruntfile.js for example)
- npm install grunt-contrib-uglify --save-dev
- npm install grunt-contrib-watch --save-dev
- npm install grunt-sass --save-dev
- then run 'grunt watch' (watches for changes), 'grunt build' (production build), or 'grunt' (development build)