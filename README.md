perlin
======

A javascript perlin noise generator.

### Examples

[Simple Perlin Blocks](http://bl.ocks.org/d2fn/8777d620caef32959713)

[Perlin Curves I](http://bl.ocks.org/d2fn/0d3789278f3d9816e0fd)

[Perlin Curves II](http://bl.ocks.org/d2fn/60f517d7a617990ed45e)

### Code

```javascript
// create a noise generator at the given scale
var noise = perlin.noise(0.1);
// get the noise value in 2 space
var value = noise(x, y);
// in 3 space
var value3 = noise(x, y, z);
```
