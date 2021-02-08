# Front Left Logo

[Access here](https://front-left.github.io/fl-logo/index.html)

Built with Node and Three.js.

JS is bundled together using Browserify, so no need to build with node. Logo.js contains original code, LogoBundle.js contains code bundled with requirements e.g. Three.js

## To Run (locally, with node):

* run: npm install http-server -g (need to run with http-server to workaround same origin policy for asset files)
* run: http-server
* navigate to the specified address, e.g. localhost:8080/index.html

### To build, if you make changes to JavaScript

* npm i browserify -g
* browserify Logo.js > LogoBundle.js
