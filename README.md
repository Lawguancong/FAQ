# FAQ

typeof null //"object"
typeof NaN // "number"
Object.prototype.toString.call(NaN) // "[object Number]"
0 === -0 //true
NaN === NaN //false
Object.is(0, -0) // false
Object.is(NaN, NaN) // true