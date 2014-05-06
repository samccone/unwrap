<h1 align="center">unwrap</h1>
<p align="center">
  <img src="https://github.com/samccone/unwrap/blob/master/logo.png"/>
</p>

A tool to remove a UMD wrap from a given file.


## How To

`npm install unwrap`

### CLI

`./node_modules/.bin/unwrap <PATH_TO_JS> > my_unwrapped_file.js`

### API

```js
require('unwrap')("path_to_file.js", function(e, unwrapped) {

});
```