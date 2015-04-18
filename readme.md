# rest-param [![Build Status](https://travis-ci.org/stoeffel/rest-param.svg)](https://travis-ci.org/stoeffel/rest-param) [![npm version](https://badge.fury.io/js/rest-param.svg)](http://badge.fury.io/js/rest-param) [![Coverage Status](https://coveralls.io/repos/stoeffel/rest-param/badge.svg?branch=master)](https://coveralls.io/r/stoeffel/rest-param?branch=master)

> Returns a function with an appended rest param


## Install

```
$ npm install --save rest-param
```


## Usage

```js
var restParam = require('rest-param');

restParam(function(a, b, rest) {
  console.log(a); // 1
  console.log(b); // 2
  console.log(rest); // [3, 4]
})(1, 2, 3, 4);
```


## API

### restParam(fn)

#### fn

*Required*  
Type: `function`


## License

MIT © [stoeffel](http://schtoeffel.ch)
