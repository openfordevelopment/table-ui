# iui-table
Angular dynamic table directive

## Setup

Add to package.json:
```javascript
"dependencies": {
    ...
    "table-ui": "git+ssh://git@github.com/openfordevelopment/table-ui.git"
}
```


## Installation (with Influence Health ui-core)

Use in app.js:
```javascript
ui.use(require('table-ui'));
```


## Installation (without ui-core / typical)

Everything you need is already minified
node_modules/table-ui/dist/table-ui.min.js

As soon as you've got the file included in your page you just need to declare a dependency on the iui.table module:
angular.module('myModule', ['iui.table']);

## Build
**Note:** if you make changes, you must run **gulp** to rebuild the combined files in the 'dist' directory. You may need to also update the package.json version number.

## Changelog

### 1.0.0

Created table-ui repo
