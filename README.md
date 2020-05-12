# rgb-random-color

> Generates a single color randomly.

## Installation

```sh
$ npm install rgb-random-color
```

## Usage

```javascript
'use strict';

const { randomColor } = require("rgb-random-color");

console.log(randomColor());

// #6cca5f

// When you need a different color to each element in an array 

const markers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

markers.map(marker => {
    console.log(randomColor());

})

/** 
 * Output : 
 
    #2634be
    #6d8cf9
    #146fb0
    #cdcfd0
    #c1474b
    #dc5f1e
    #dd0130
    #6f470e
    #96f011
    #a6e0ec
 */

```

## License

ISC