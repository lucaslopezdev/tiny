# @lucaslopezdev/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@lucaslopezdev/tiny.svg)](https://github.com/lucaslopezdev/tiny)
[![npm bundle size](https://shields-io.translate.goog/bundlephobia/min/tiny)](https://github.com/lucaslopezdev/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
// => "Somuchspace!"

tiny(1337);
// => Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
