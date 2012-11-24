# Vec2

## Information
This plugin for the [Impact Game Engine](http://impactjs.com/) adds, easy to use, class for two-dimensional vector and assorted functions to your project.

## Usage
1. Put it in your plugins directory.
2. Add it in the requires of your main.js.
3. Use it like this:

```javascript
var vec1 = ig.Vec2(1, 2);
var vec2 = ig.Vec2(3, 4);
vec1.add(vec2);
vec2.norm();
var vec3 = ig.Vec2.sum(vec1, vec2);
```

## Supported operations
Check the vec2.js ...

## TODO
* Did you miss a vector operation? Contact me ...

## Changelog
### v1.0.0
* first commit

## Credits
Based on [Googles Closure Library math.Vec2](https://code.google.com/p/closure-library/source/browse/trunk/closure/goog/math/vec2.js)