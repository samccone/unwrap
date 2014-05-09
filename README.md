<h1 align="center">unwrap</h1>
<p align="center">
  <img width="300px" src="https://raw.githubusercontent.com/samccone/unwrap/master/logo.png"/>
</p>

A tool to remove a UMD wrap from a given file.
[![Build Status](https://travis-ci.org/samccone/unwrap.svg)](https://travis-ci.org/samccone/unwrap)

## How To

`npm install unwrap`

### CLI

`./node_modules/.bin/unwrap <PATH_TO_JS> > my_unwrapped_file.js`

### API

```js
require('unwrap')("path_to_file.js", function(e, unwrapped) {

});
```
