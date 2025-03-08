#JS_Elzero 
```js
/*
  String Methods
  - Access With Index
  - Access With charAt()
  - length
  - trim()
  - toUpperCase()
  - toLowerCase()
  - Chain Methods
*/

let theName = "Ahmed";

console.log(theName);      //Ahmed
console.log(theName[1]);   //h
console.log(theName[5]);   //undefined

console.log(theName.charAt(1));   //h
console.log(theName.charAt(5));   //empty string ("")

console.log(theName.length);   //5   

let theName = "  Ahmed  ";

console.log(theName[1]);   //" " (space)
console.log(theName[5]);   //e

console.log(theName.charAt(1));   //" " (space)
console.log(theName.charAt(5));   //e

console.log(theName.length);   //9 
console.log(theName.trim());   //Ahmed

console.log(theName.toUpperCase());  //  AHMED
console.log(theName.toLowerCase());  //  ahmed

console.log(theName.trim().charAt(2).toUpperCase());   //M
```

*Note: Index Starts from 0 Not 1.*

**Trim** => Removes the leading and the trailing white space.