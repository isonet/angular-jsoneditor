# angular-jsoneditor [![npm](https://img.shields.io/npm/v/angular-jsoneditor.svg?style=flat-square)](https://github.com/isonet/angular-jsoneditor)[![licence](https://img.shields.io/npm/l/angular-jsoneditor.svg?style=flat-square)](https://img.shields.io/npm/l/angular-jsoneditor.svg)[![Codacy grade](https://img.shields.io/codacy/grade/5483756bdff94ba6bc1bf530b24a3221.svg?style=flat-square)](https://github.com/isonet/angular-jsoneditor)

I have forked this jsoneditor to make a readOnly option that works.
If you would like to make a readOnly json editor it will only work on 'text' mode.
Just pass 'readOnly: true' property in the 'options' object.

Angular wrapper for [jsoneditor](https://github.com/josdejong/jsoneditor)

## Requirements

- Only AngularJS, the rest is bundled


## Usage

NPM:

```sh
npm install --save angular-jsoneditor
```


Don't forget to include the files in your app:

```html
<script src="/node_modules/angular-jsoneditor/dist/angular-jsoneditor.js"></script>
```

OR

```javascript
import 'angular-jsoneditor';
```

Add the 'angular-jsoneditor' module as a dependency to your application module:

```javascript
const app = angular.module('app', ['angular-jsoneditor']);
```

Finally, add the directive to your html:

```html
<angular-jsoneditor ng-model="data" options="options" style="width: 100%; height: 400px;"></angular-jsoneditor>
```

## Demo

Check the html file in the demo folder or [try this fiddle](https://jsfiddle.net/kdhky4v9/2/)



### Options

Please refer to the jsoneditor API for the different options.

### Licence

MIT: see LICENSE
