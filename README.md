express3-dynamic-helpers-patch
==============================

Dynamic helpers monkey patch for express 3.x

### How to install?

```js
  npm install express3-dynamic-helpers-patch --save
```

### How to use It?

```js
  require('express3-dynamic-helpers-patch')(app);
  // and now You can use 2.x express dynamicHelpers
  app.dynamicHelpers({
    user: function (req, res) {
      ...
    }
  });
```

License: MIT
