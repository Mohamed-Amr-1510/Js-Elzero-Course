#JS_Elzero 

```js
/*
  Switch Statement
  switch(expression) {
    Case 1:
      // Code Block
      break;
    Case 2:
      // Code Block
      break;
    Default:
      // Code Block
  }
  - Default Ordering
  - Multiple Match
  - ===
*/

let day = "A";

switch (day) {
  default:
    console.log("Unknown Day");
    break;
  case 0:
    console.log("Saturday");
    break;
  case 1:
    console.log("Sunday");
    break;
  case 2:
  case 3:
    console.log("Monday");
    break;
}
```

### Switch Statement :
```js
switch (expression) {
  case value1:
    // Code block for value1
    break;
  case value2:
    // Code block for value2
    break;
  case value3:
  case value4:
    // Code block for value3 and value4
    break;
  default:
    // Code block if no cases match
    break;
}
```

### Notes : 
- In Switch We use the identical (strict equality) in comparison (=\=\=).
- The `default` case doesn't have to be at the end of the switch statement.



