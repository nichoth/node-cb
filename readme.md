# node cb

Convert a function that takes two callbacks for success and error to a function that takes a single node style callback.

## example

```js

var wrap = require('node-cb');

function example(success, err) {}
var wrapped = wrap(example);

wrapped(function(err, res) {});

```
