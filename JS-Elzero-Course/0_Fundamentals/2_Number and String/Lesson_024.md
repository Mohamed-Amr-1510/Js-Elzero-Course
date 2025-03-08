#JS_Elzero 

```js
/*
  Number Methods
  - Two Dots To Call A Methods
  - toString()
  - toFixed()
  - parseInt()
  - parseFloat()
  - isInteger() [ES6]
  - isNaN() [ES6]
*/

console.log((100).toString());    //Convert Number => string
console.log(100.10.toString());

console.log(100.555555.toFixed(2));  //10.56 (String)
console.log(100.554555.toFixed(2));  //10.55 (String)

console.log(Number("100 Osama"));         //NaN
console.log(+"100 Osama");                //NaN
console.log(parseInt("100 Osama"));       //100 (Number)
console.log(parseInt("Osama 100 Osama")); //NaN
console.log(parseInt("100.500 Osama"));   //100
console.log(parseFloat("100.500 Osama")); //100.5

console.log(Number.isInteger("100"));    //false
console.log(Number.isInteger(100.500));  //false
console.log(Number.isInteger(100));      //true

console.log(Number.isNaN("Osama"));       //false
console.log(Number.isNaN("Osama" / 20));  //true
```

#### Two Dots To Call A Methods :
 ```js
 console.log((100).toString()); = console.log(100..toString()); 
```
 We put 2 dots because if We use one The language will suppose that We will write a float number.
 
 *Note: That happens When the formatter is closed*


#### Number.isNaN:
 It doesn't check that the value is a number or not but It checks if the value is exactly `NaN`. 