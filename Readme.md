
# touchaction-property

  Returns &quot;touchAction&quot;, &quot;msTouchAction&quot;, or null.
  See: http://msdn.microsoft.com/en-us/library/windows/apps/hh767313.aspx

## Installation

  Install with [component(1)](http://component.io):

    $ component install component/touchaction-property

## API

``` js
var touchAction = require('touchaction-property');

if (touchAction) {
  document.body.style[touchAction] = 'none';
}
```

## License

  MIT
