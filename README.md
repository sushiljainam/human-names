# random-human-names v2.0.4 [![Build Status](https://travis-ci.org/AlessandroMinoccheri/human-names.svg?branch=master)](https://travis-ci.org/AlessandroMinoccheri/human-names)

Get popular human english, italian, french, deutch, spanish or dutch names.

To create this repository I have forked this project and make some edit:

https://github.com/sindresorhus/supervillains

Thanks to the author https://github.com/sindresorhus

The name lists are just JSON files and can be used wherever.



## Install

```
$ npm install --save random-human-names
```


## Usage

```js
var humanNames = require('random-human-names');

humanNames.femaleRandom();
//=> Lucy
```


## API

### .female

Type: `array`

Top female names sorted by popularity.

### .male

Type: `array`

Top male names sorted by popularity.

### .all

Type: `array`

Top names sorted by popularity.

### .femaleRandom()

Type: `function`

Random female name.

### .maleRandom()

Type: `function`

Random male name.

### .allRandom()

Type: `function`

Random name.


## License

MIT © [Alessandro Minoccheri](http://alessandrominoccheri.com)
