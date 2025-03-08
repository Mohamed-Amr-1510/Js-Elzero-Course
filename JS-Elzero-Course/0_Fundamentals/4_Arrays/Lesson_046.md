#JS_Elzero 

```js
/*
  Arrays Methods [Joining]
  - concat(array, array) => Return A New Array
  - join(Separator)
*/

let myFriends = ["Ahmed", "Sayed", "Ali", "Osama", "Gamal", "Ameer"];
let myNewFriends = ["Samar", "Sameh"];
let schoolFriends = ["Haytham", "Shady"];

let allFriends = myFriends.concat(myNewFriends, schoolFriends, "Gameel", [1, 2]);

console.log(allFriends);
//["Ahmed", "Sayed", "Ali", "Osama", "Gamal", "Ameer","Samar", "Sameh","Haytham", "Shady","Gameel", 1, 2]

console.log(allFriends.join());
console.log(allFriends.join(""));
console.log(allFriends.join(" @ "));
console.log(allFriends.join("|"));
console.log(allFriends.join("|").toUpperCase());
//AHMED|SAYED|ALI|OSAMA|GAMAL|AMEER|SAMAR|SAMEH|HAYTHAM|SHADY|GAMEEL|1|2
```

#### Notes :
- **Concat** : is treating with a new array , The old arrays are untouched.
- You can Add items ( "Gameel" ) and Arrays  ( \[1, 2]  , myNewFriends ) with **Concat**.
- **Join** : converts an array's elements into a **string** and separates between them using a separator.
- If We don't write a specified separator , it will use the default **,** (**coma**).
