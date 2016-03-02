# Grunt Demo

- Requires Node.js
    - There are various ways to install Node.js. See the following for suggestions:
    - https://nodejs.org/
    - http://www.nearform.com/nodecrunch/nodejs-sudo-free/
    - http://benznext.com/completely-uninstall-node-js-from-mac-os-x/
    - http://treehouse.github.io/installation-guides/mac/node-mac.html
- Run the following commands from your project folder:
    - `npm init` - Initializes and creates the `package.json` file
    - `npm install grunt --save-dev` - Installs Grunt and adds configuration to the `package.json` file
    - `npm install grunt-contrib-uglify --save-dev` - Minify JavaScript files
    - `npm install grunt-contrib-watch --save-dev` - Watch for file system changes
    - `npm install grunt-sass --save-dev` - Compile Sass files
    - Configure `gruntfile.js` (see the `gruntfile.js` for an example)
    - Run `grunt watch` to watch for changes, `grunt build` to build for production, or `grunt` to build for development

Original reference: http://teamtreehouse.com/library/up-and-running-with-grunt
