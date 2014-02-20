*This repository is a mirror of the [component](http://component.io) module [gamtiq/isarray-shim](http://github.com/gamtiq/isarray-shim). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/gamtiq-isarray-shim`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# isarray-shim

Shim for ECMAScript 5 Array.isArray

## Installation

Install component:

    npm install -g component

Then:

    component install gamtiq/isarray-shim

## Usage

    var isArray = require("isarray-shim");
    ...
    var test1 = Array.isArray(someObj1);
    var test2 = isArray(someObj2);

## Licence

MIT

