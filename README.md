# Setup

* Clone the repo with the desired project name (or leave as `simple-webpack-starter`)
* Delete the `.git` directory at the project root and initialize your own git repo with `git init`
* `webpack.config.js` will default to using the package name for output file names
  * If desired edit `name` in `package.json`
  * Alternatively, edit `libraryName` in `webpack.config.js`, or alter the output file generation as desired in the webpack config
* Run `npm install`
* Commands to build, run, serve are described in `package.json`