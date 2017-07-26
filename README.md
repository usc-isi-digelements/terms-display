# terms-display

A Polymer Element showing the keys and values of an object collection.

### Example
```js
var collection = {
  Key1: ['Value1'],
  Key2: ['Value2', 'Value3'],
  Key3: []
};
```

```html
<terms-display
  collection="[[collection]]">
</terms-display>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

