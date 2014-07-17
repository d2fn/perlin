perlin
======

A javascript perlin noise generator.

[Example on bl.ocks.org](http://bl.ocks.org/d2fn/8777d620caef32959713)

```javascript
// create a noise generator at the given scale
var noise = perlin.noise(0.1);
// get the noise value in 2 space
var value = noise(x, y);
// in 3 space
var value3 = noise(x, y, z);
```
