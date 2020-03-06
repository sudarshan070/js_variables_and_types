## Go through the [comparision](http://javascript.info/comparison) chapter and complete the task below.

Write the output (true / false) next to the comparision done below.

```js
"hello world" === "hello world"; // Output

"hello world" == "hello world"; // true

true === true; // true

77 == "77"; //true

77 === "77"; //false    //strict equality

"cat" === "dog"; // false

false === 0; // false

false == 0; // true    // regular equality cannot differentiate 0 from false

0 == ""; // true

"" == false; // true

null == null; // true

undefined == undefined; // true

null == undefined; // true // null & undefined is equal to each other (==) but not other value

null == 0; // false   //equality check

null == 21; // false

null == "null"; // false

undefined == "undefined"; // false

undefined == 0; // false  // undefined gets converted to NaN

undefined == false; // false

undefined == "false"; // false

NaN == null; //  false  // Nan is a  special numeric value which returns false for all comparisons.

NaN == "NaN"; // false

NaN == 0; // false

NaN == false; // false

NaN == undefined; // false

NaN == NaN; // false

2 > 1; // true

2 != 1; // true

"Z" > "A"; // true    // Strings are compared letter-by-letter.

"Hello World" > "Super Mario"; // false

"Hello World" != "Super Mario"; // true

NaN !== NaN; // true

NaN != NaN; // true

NaN != undefined; // true

undefined != null; //  false   undefined & null are eual to each other

undefined != "Hello"; // true

undefined != "undefined"; // true
```
