# @rseikel/tiny
![npm (scoped)](https://img.shields.io/npm/v/@rseikel/tiny)
Removes all spaces from a string.

Install

$ npm install @rseikel/tiny
Usage

const tiny = require("@rseikel/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
