# simple-time-log
Logs stuff. If you pass in multiple arguments it will join them by a space. Extracted from [gulp-util](https://github.com/gulpjs/gulp-util)

## Installation
  `npm install simple-time-log --save`

## Usage

```javascript
var log = require('simple-time-log')

var accounts = [{
    name: 'alice',
    inUse: true
  },{
    name: 'bob'
  },{
    name: 'charlie'
  }]

log('accounts', accounts)
// =>
// [13:44:40] accounts [{
//     name: 'alice',
//     inUse: true
//   },{
//     name: 'bob',
//     inUse: false
//   },{
//     name: 'charlie',
//     inUse: false
//   }]
```

# License
MIT
