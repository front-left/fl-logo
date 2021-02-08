# Front Left Logo

Built with Node and Three.js.

JS is bundled together using Browserify.

## To Run (locally, with node):

* run: npm i
* run: npm install http-server (need to run with http-server to workaround same origin policy for asset files)
* run: http-server
* navigate to the specified address, e.g. localhost:8080/index.html

### To build, if you make changes to JavaScript

* npm i browserify -g
* browserify Logo.js > LogoBundle.js
