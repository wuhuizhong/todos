[![Circle CI](https://circleci.com/gh/meteor/todos.svg?style=svg)](https://circleci.com/gh/meteor/todos)

This is a Todos example app built on the principles described in the [Meteor Guide](http://guide.meteor.com/structure.html). This app uses the module functionality introduced in Meteor 1.3, but everything else should be applicable to Meteor 1.2 as well.

## Versions

This version (the `master`) branch uses the [Blaze](http://guide.meteor.com/blaze.html) rendering library, with code written in ES2015 JavaScript.

The [`react`](https://github.com/meteor/todos/tree/react) branch implements the same application using [React](http://guide.meteor.com/react.html)

The [`coffeescript`](https://github.com/meteor/todos/tree/coffeescript) branch implements this (the Blaze) version of the app in CoffeeScript.

Note that attempts will be made to keep the branches up to date but this isn't guaranteed.

### Running the app

```bash
meteor npm install
meteor
```

### Scripts

To lint:

```bash
meteor npm run lint
```

Note: you are using a pure-JavaScript implementation of bcrypt.
While this implementation will work correctly, it is known to be
approximately three times slower than the native implementation.
In order to use the native implementation instead, run
```bash
meteor npm install --save bcrypt
```
in the root directory of your application.
