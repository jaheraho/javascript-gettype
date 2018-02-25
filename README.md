getType
=================

```js
var undef;
getType('hello github');// -> string
getType(1337);// -> number
getType(false);// -> boolean
getType(1.2);// -> float
getType({});// -> object
getType([1, 2]);// -> array
getType(null);// -> null
getType(undef);// -> undefined
getType(new RegExp('0-9'));// -> regexp
getType(function(){});// -> function
getType(new Date('2013-04-09'));// -> date
getType(new Error('something is wrong here!'));// -> error
```

License
-------

The project is licensed under the MIT license.