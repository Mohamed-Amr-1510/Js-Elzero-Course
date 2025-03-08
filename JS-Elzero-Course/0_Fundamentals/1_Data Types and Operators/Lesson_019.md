#JS_Elzero 
```js
/*
  - + Unary Plus [Return Number If Its Not Number]
  - - Unary Negation [Return Number If Its Not Number + Negates It]
  Tests
  - Normal Number
  - String Number
  - String Negative Number
  - String Text
  - Float
  - Hexadecimal Numeral System => 0xFF
  - null
  - false
  - true
*/

console.log(+100);             //100
console.log(+"100");           //100 (Number) 
console.log(+"-100");          //100 (Number) 
console.log(+"Osama");         //NaN (Number) 
console.log(+"15.5");          //15.5 (Number) 
console.log(+0xff);            //255
console.log(+null);            //0 (Number) 
console.log(+false);           //1 (Number) 
console.log(+true);            //1 (Number) 

console.log(-100);             //-100
console.log(-"100");           //-100 (Number) 
console.log(-"-100");          // 100 (Number) 
console.log(-"Osama");         //NaN
console.log(-"15.5");          //-15.5 (Number) 
console.log(-0xff);            //-255 (Number) 
console.log(-null);            // -0
console.log(-false);           // -0
console.log(-true);            // -1

console.log(Number("100")); // also used to convert strings to a number
```

