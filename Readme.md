*This repository is a mirror of the [component](http://component.io) module [component/format-parser](http://github.com/component/format-parser). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-format-parser`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# format-parser

  Declarative format parser for declarative template engines

## Installation

    $ component install component/format-parser

## Example

```js
var parse = require('format-parser');
parse('created_at | date:"%Y %M %d"');
```

## License

  MIT
