## v0.6.0 - Mar 1 2015

* **[Breaking]** react-spin now uses ES6 modules through Babel. If you use ES6 modules, you shouldn't have to change anything. If you use CommonJS, you'll now need to import react-spin like so:

```js
// before
var Spinner = require('react-spin');

//after
var Spinner = require('react-spin').default;
```

* Spinners created with `stopped` set to true will now be stopped by default (thanks [lobobabysaurus](https://github.com/lobobabysaurus))
