#typeis.js
##Typeis. it's the smart and simple javaScript type checker;

###installation
```javascript
npm install typeis --save
```

###usage

####nodejs
```javascript
require('typeis');
```
####browser
```html
<script src="node_modules/typeis/typeis.js"></script>
```
####examples
```javascript
var regexp = /test/gi
var arr = ['test'];
var now = new Date();
var obj = {};

console.log(regexp.typeis()); //RegExp;
console.log(regexp.typeis('regexp')); //true;
console.log(regexp.typeis('object')); //false;
console.log(arr.typeis()); //RegExp;
console.log(arr.typeis('array')); //true;
console.log(now.typeis()); //Date;
console.log(obj.typeis()); //Object;
```