#JS_Elzero 

```js
/*
  String Methods
  - indexOf(Value [Mand اجبارى], Start [Opt اختيارى] 0)
  - lastIndexOf(Value [Mand], Start [Opt] Length)
  - slice(Start [Mand], End [Opt] Not Include End)
  - repeat(Times) [ES6]
  - split(Separator [Opt], Limit [Opt])
*/

let a = "Elzero Web School";

console.log(a.indexOf("Web"));      // 7
console.log(a.indexOf("Web", 8));   // -1
console.log(a.indexOf("o"));        // 5
console.log(a.lastIndexOf("o"));    // 15

console.log(a.slice(2, 6));         //zero
console.log(a.slice(-5, -3));       //ch

console.log(a.repeat(5));          
//Elzero Web SchoolElzero Web SchoolElzero Web SchoolElzero Web SchoolElzero Web School
console.log(a.split());         // Elzero Web School will return but as array.
console.log(a.split(""));       // An Array of individual characters .
/*[ "E", "l", "z", "e", "r", "o", " ", "W", "e", "b", " ", "S", "c", "h", "o", "o", "l",]*/
console.log(a.split(" "));     // ["Elzero", "Web", "School"]
console.log(a.split("", 6));   // ["E", "l", "z", "e", "r", "o"]
```

#### Slice
-  Not Include The End
- If We write Negative numbers it will count from the end.