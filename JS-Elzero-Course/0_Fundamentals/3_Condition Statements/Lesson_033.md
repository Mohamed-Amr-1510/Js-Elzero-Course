#JS_Elzero 

```js
/*
  Control Flow
  - if
  - else if
  - else

  if (Condition) {
    // Block Of Code
  }

*/

let price = 100;
let discount = true;
let discountAmount = 30;
let country = "KSA";

if (discount === true) {
  price -= discountAmount; // price = price - discountAmount
} else if (country === "Egypt") {
  price -= 40;
} else if (country === "Syria") {
  price -= 50;
} else {
  price -= 10;
}

console.log(price);
```

### IF Condition Syntax :
```js
if (Condition1) {           // Check Condition 1 first
    // Block 1                    // If true, execute Block 1 and stop checking
} else if (Condition2) {    // If Condition 1 is false, check Condition 2
    // Block 2                   // If true, execute Block 2 and stop checking
} else if (Condition3) {   // If Condition 2 is false, check Condition 3
    // Block 3                   // If true, execute Block 3 and stop checking
} else {                   // If all conditions are false, execute this
    // Block 4           
}

