#JS_Elzero 

```js
/*
  Logical Or ||
  -- Null + Undefined + Any Falsy Value
  Nullish Coalescing Operator ??
  -- Null + Undefined
*/

console.log(Boolean(100));    //true
console.log(Boolean(-100));   //true
console.log(Boolean(0));      //false
console.log(Boolean(""));     //false
console.log(Boolean(null));   //false

let price = 0;

console.log(`The Price Is ${price || 200}`);   // 200
//In the case the price has a falsy value (null,(empty string)"", undefined, 0, false, NaN), use 200.

console.log(`The Price Is ${price ?? 200}`);   // 0
//In the case the price is (null , undefined)
```

