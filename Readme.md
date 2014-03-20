*This repository is a mirror of the [component](http://component.io) module [manuelstofer/foreach](http://github.com/manuelstofer/foreach). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/manuelstofer-foreach`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# foreach

Iterate over the key value pairs of either an array-like object or a dictionary like object.

[![browser support][1]][2]

## API

### foreach(object, function, [context])

```js
var each = require('foreach');

each([1,2,3], function (value, key, array) {
    // value === 1, 2, 3
    // key === 0, 1, 2
    // array === [1, 2, 3]
});

each({0:1,1:2,2:3}, function (value, key, object) {
    // value === 1, 2, 3
    // key === 0, 1, 2
    // object === {0:1,1:2,2:3}
});
```

[1]: https://ci.testling.com/manuelstofer/foreach.png
[2]: https://ci.testling.com/manuelstofer/foreach

