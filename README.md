# drtis-color-palette-generator [![Build Status](https://travis-ci.org/Dr-TIS/color-palette-generator.svg?branch=master)](https://travis-ci.org/Dr-TIS/color-palette-generator)

## Example

```js
const colorGen = require("drtis-color-palette-generator"); // colorGen(baseColor, numberOfColorsToGenerate, mixOutput)

console.log(colorGen("#D60000", 12)); // [ '#D60000', '#D64700', '#D68F00', '#D6D600', '#8FD600', '#47D600', '#00D600', '#00D647', '#00D68F', '#00D6D6', '#008FD6', '#0047D6' ]

console.log(colorGen("#D60000", 12, true)); // [ '#D60000', '#00D600', '#D64700', '#00D647', '#D68F00', '#00D68F', '#D6D600', '#00D6D6', '#8FD600', '#008FD6', '#47D600', '#0047D6' ]
```
