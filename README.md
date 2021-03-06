# clean-start
A simple clean webpack 5, babel 8, sass, css, and externalized stylesheet project setup for use.

`npx clean-start app-name` to create a base webpack/babel/sass setup into `app-name` folder.


## Basic setup
This project is a preconfigured setup for the common modern toolchains.  Every tutorial assumes React or some other tools that not everyone uses.  This config will only config the following libraries and tools:

* Webpack 5 
* Babel 8
* SASS
* Mocha
  - chai
  - jsdom

## Commands
The supported npm commands with this build are the following:

* npm run dev
  - build to dist and creates a separate css file and bundle.js
* npm run build
  - build to dist and creates a separate css file and bundle.js minified
* npm run rebuild
  - completely clears node_modules and rebuilds
* npm run reinstall
  - completely clears node_modules and installs
* npm test
  - runs babel and executes mocha against the test folder
