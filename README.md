[![Build Status](https://travis-ci.org/dynamicbalaji/dynamic-pluralize.svg?branch=master)](https://travis-ci.org/dynamicbalaji/dynamic-pluralize)
[![Coverage Status](https://coveralls.io/repos/github/dynamicbalaji/dynamic-pluralize/badge.svg?branch=master)](https://coveralls.io/github/dynamicbalaji/dynamic-pluralize?branch=master)

# dynamic-pluralize

A Node.js module that returns the plural or singular form of any noun

## Installation 
```sh
npm install dynamic-pluralize --save
yarn add dynamic-pluralize
bower install dynamic-pluralize --save
```

## Usage

### Javascript
```javascript
var pluralise = require('dynamic-pluralize');
var boys = pluralise.getPlural('Boy');
```
```sh
Output should be 'Boys'
```

### TypeScript
```typescript
import { getPlural } from 'dynamic-pluralize';
console.log(getPlural('Goose'))
```
```sh
Output should be 'Geese'
```

### AMD
```javascript
define(function(require,exports,module){
  var pluralise = require('dynamic-pluralize');
});
```

## Test 
```sh
npm run test
```

## Set your npm defaults

```sh
npm set init.author.name “Balaji Ashokkumar”
npm set init.author.email “dynamicbalaji4u@gmail.com”
npm set init.author.url “https://github.com/dynamicbalaji"
```

## Initialize a npm package

```sh
npm init
```

```sh
npm init -y     // Skip questions and create package.json with defaults
```

