<<<<<<< HEAD
# ember-string-ishtmlsafe-polyfill [![Build Status](https://travis-ci.org/workmanw/ember-string-ishtmlsafe-polyfill.svg?branch=master)](https://travis-ci.org/workmanw/ember-string-ishtmlsafe-polyfill)

This provides a polyfill for the `Ember.String.isHTMLSafe` feature added in Ember 2.8.

RFC: [emberjs/rfcs#139](https://github.com/emberjs/rfcs/pull/139).

PR: [emberjs/ember.js#13666](https://github.com/emberjs/ember.js/pull/13666).

API: [Ember.String.isHTMLSafe](http://emberjs.com/api/classes/Ember.String.html#method_isHTMLSafe)

=======
my-addon
==============================================================================

[Short description of the addon.]
>>>>>>> 06dc7c6... message

Installation
------------------------------------------------------------------------------

```
<<<<<<< HEAD
ember install ember-string-ishtmlsafe-polyfill
```


## Usage

```javascript
import Ember from 'ember';

var plainString = 'plain string';
var safeString = Ember.String.htmlSafe('<div>someValue</div>');

Ember.String.isHTMLSafe(plainString); // false
Ember.String.isHTMLSafe(safeString);  // true
```


## Migration

### Applications

After you upgrade your application to Ember 2.8, you should remove `ember-string-ishtmlsafe-polyfill`
from your `package.json`.

### Addons

Addons generally support many different Ember versions, so leaving `ember-string-ishtmlsafe-polyfill`
in place for consumers of your addon is perfectly normal.  When the addon no longer supports
Ember versions older than 2.8, we recommend removing `ember-string-ishtmlsafe-polyfill` from
your `package.json` and doing a major version bump.


## Compatibility

This addon is tested against each minor Ember version starting with 1.10 through 2.8
(when `isHTMLSafe()` landed). Additionally tested against, `ember-stable`, `ember-beta`,
and `ember-canary`. A complete list can be found in the
[`ember-try.js`](https://github.com/workmanw/ember-string-ishtmlsafe-polyfill/blob/master/config/ember-try.js)
config.

=======
ember install my-addon
```


Usage
------------------------------------------------------------------------------

[Longer description of how to use the addon in apps.]


Contributing
------------------------------------------------------------------------------

### Installation

* `git clone <repository-url>`
* `cd my-addon`
* `npm install`

### Linting

* `npm run lint:js`
* `npm run lint:js -- --fix`
>>>>>>> 06dc7c6... message

### Running tests

<<<<<<< HEAD
* `npm test` (Runs `ember try:each` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`
=======
* `ember test` – Runs the test suite on the current Ember version
* `ember test --server` – Runs the test suite in "watch mode"
* `npm test` – Runs `ember try:each` to test your addon against multiple Ember versions

### Running the dummy application

* `ember serve`
* Visit the dummy application at [http://localhost:4200](http://localhost:4200).

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).

License
------------------------------------------------------------------------------

This project is licensed under the [MIT License](LICENSE.md).
>>>>>>> 06dc7c6... message
