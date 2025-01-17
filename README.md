# OpenCV4js

![npm](https://img.shields.io/npm/v/opencv4js)
![npm bundle size](https://img.shields.io/bundlephobia/min/opencv4js)
![Libraries.io SourceRank](https://img.shields.io/librariesio/sourcerank/npm/opencv4js) <!-- ![Depfu](https://img.shields.io/depfu/arghyadeep-k/opencv4js) --> 
![Snyk Vulnerabilities for npm package](https://img.shields.io/snyk/vulnerabilities/npm/opencv4js)
![npm](https://img.shields.io/npm/dt/opencv4js)
![NPM](https://img.shields.io/npm/l/opencv4js?color=blue)

## Description
This is the official OpenCV.js file packaged into a npm package for ease of use with no modifications in code whatsoever. 

Please note that this package is not maintained by the OpenCV team/contributors. 

<br>

## Why OpenCV4js?

This package is updated whenever a new OpenCV version is released officially. By using the package in your OpenCV based Node.js project, you don't need to manually place the opencv.js file or worry about keeping it up to date later.

`npm update` will automatically fetch the updates, if any, just like any other package.

Also, the release numbers are synced with the official OpenCV releases for easy tracking. (Available 3.0+ only)

<br>


## Installation

[![NPM](https://nodei.co/npm/opencv4js.png)](https://nodei.co/npm/opencv4js/)

### Install from command line
`npm i --save opencv4js`

<br>

## Usage

With this package, you can skip placing the opencv.js file (as mentioned in the tutorials) and use the following code to import it:
```javascript
cv = require('opencv4js');
``` 

instead of 

```javascript
cv = require('./opencv.js');
```

Or

Replace 
```javascript
global.cv = require('./opencv.js');
``` 
with 
```javascript
global.cv = require('opencv4js');
```
<br>

Rest of the usage will be similar to the official <a href="https://docs.opencv.org/master/dc/de6/tutorial_js_nodejs.html">docs</a> and no other changes are required.

<br>

## License
OpenCV4js is published under the Apache 2.0, same license as the official OpenCV. 
For more information, see the accompanying LICENSE file. 
