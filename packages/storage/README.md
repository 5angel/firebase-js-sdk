# @firebase/storage

This is the storage component for the Firebase JS SDK. It has a peer
dependency on the [`@firebase/app`](https://npm.im/@firebase/app) package on NPM. This package
is included by default in the [`firebase`](https://npm.im/firebase) wrapper
package.

## Installation

You can install this package by running the following in your project:

```bash
$ npm install @firebase/storage
```

## Usage

You can then use the firebase namespace exposed by this package as illustrated
below:

**ES Modules**

```javascript
import firebase from '@firebase/app';
import '@firebase/storage'

// Do stuff w/ `firebase` and `firebase.storage`
```

**CommonJS Modules**

```javascript
const firebase = require('@firebase/app').default;
require('@firebase/storage');

// Do stuff with `firebase` and `firebase.storage`
```

## Documentation

For comprehensive documentation please see the [Firebase Reference
Docs][reference-docs].

[reference-docs]: https://firebase.google.com/docs/reference/js/
