underscore-x
============

Extend some features from underscore for more complicated cases. 


-------------


## Purpose
The purpose of this module is to cover some complicated cornerstone cases on some object or array transformation (or any JS features) not covered by underscore.js.

## Installation
    $ npm install underscore-x

## Quick Start

```js
    var _ = require('underscore-x');
    
    var output = {};
    
    _.extend_x(output, {a:123});

   // output is {a:123}
   
    var output = {a1:{b1:"h", b2:123}, a2:[1,2,3,4]};
    
    _extend_x(output, {a1:{b1:"b1", b3:[1,2,3], b4:"b4"}, a2:[3,4,5], a3:"xxx" });
    
    // output is {a:{b1:"b1", b2:123, b3:[123], b4:"b4"}, a2:[1,2,3,4,3,4,5], a3:"xxx"}
```

## Objects functions

    extend_d(target, sources... )

 Copy the source objects to the target object.  More... 

