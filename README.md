[![NPM](https://nodei.co/npm/isgd.png?downloads=true&downloadRank=true&stars=true)](https://nodejs.com/package/isgd/)

# Is.gd
[http://is.gd](http://is.gd) URL Shortener Node.js Module

[![Coverage Status](https://coveralls.io/repos/AlphaT3ch/is.gd/badge.svg)](https://coveralls.io/r/AlphaT3ch/is.gd)
[![Travis CI Status](https://travis-ci.org/AlphaT3ch/is.gd.svg)](https://travis-ci.org/AlphaT3ch/is.gd)

Example Shorten:

First run ```npm install isgd``` to install the Is.gd package to your system.

```javascript
var isgd = require('isgd');

isgd.shorten('http://google.com', function(res) {
	console.log(res); //Returns a shorter version of http://google.com - http://is.gd/OwycZW
});
```