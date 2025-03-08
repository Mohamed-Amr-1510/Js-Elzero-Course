#JS_Elzero 
```js
/*
  Arrays Methods [Slicing]
  - slice(Start [Opt], End [Opt] Not Including End)
  --- slice() => All Array
  --- If Start Is Undefined => 0
  --- Negative Count From End
  --- If End Is Undefined || > Indexes => Slice To The End Array.length
  --- Return New Array
  - splice(Start [Mand], DeleteCount [Opt] [0 No Remove], The Items To Add [Opt])
  --- If Negative => Start From The End
*/

let myFriends = ["Ahmed", "Sayed", "Ali", "Osama", "Gamal", "Ameer"];
console.log(myFriends); 
console.log(myFriends.slice());         //["Ahmed", "Sayed", "Ali", "Osama", "Gamal", "Ameer"]
console.log(myFriends.slice(1));        //["Sayed", "Ali", "Osama", "Gamal", "Ameer"]
console.log(myFriends.slice(1, 3));      //["Sayed", "Ali"]
console.log(myFriends.slice(-3));        //["Osama", "Gamal", "Ameer"]
console.log(myFriends.slice(1, -2));     //["Sayed", "Ali", "Osama"]
console.log(myFriends.slice(-4, -2));    //["Ali", "Osama"]
console.log(myFriends);
//["Ahmed", "Sayed", "Ali", "Osama", "Gamal", "Ameer"]

myFriends.splice(1, 2, "Sameer", "Samara");
//["Ahmed","Sameer", "Samara", "Osama", "Gamal", "Ameer"]

console.log(myFriends);
//["Ahmed","Sameer", "Samara", "Osama", "Gamal", "Ameer"]
```

**Slice**  => Returns New Array.
**Splice** => Modifies in the original array