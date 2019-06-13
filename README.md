# Effective JavaScript book notes

## Strict Mode

* Decide which versions of JavaScript your application supports.
* Always use Strict Mode in your application code
* Don't concatenate two files with different Strict Modes.
* Make sure your feature is supported in all js versions.

## Numbers

* JavaScript numbers are double-precision floating-point numbers.
* Integers in JavaScript are just a subset of doubles rather than a
separate datatype.

## Coercions

* Null coerce to 0.
* undefined coerce to NaN.
* NaN is not equal to NaN. eg:- var x = NaN; x !== x; //true
* String plus number is equal to string.
* 7 falsy values in js are false,0, -0, "", NaN, null, undefined.
* Adding + in front of any string will convert it to number.