#JS_Elzero 

```js
/*
  Arrays Methods [Search]
  - indexOf(Search Element, From Index [Opt])
  - lastIndexOf(Search Element, From Index [Opt])
  - includes(valueToFind, fromIndex [Opt]) [ES7]
*/

let myFriends = ["Ahmed", "Mohamed", "Sayed", "Alaa", "Ahmed"];

console.log(myFriends);

console.log(myFriends.indexOf("Ahmed"));              //0
console.log(myFriends.indexOf("Ahmed", 2));           //4

console.log(myFriends.lastIndexOf("Ahmed"));          //4
console.log(myFriends.lastIndexOf("Ahmed", -2));      //0

console.log(myFriends.includes("Ahmed"));            //true
console.log(myFriends.includes("Ahmed", 2));         //true

if (myFriends.lastIndexOf("Osama") === -1) {
  console.log("Not Found");
}

console.log(myFriends.indexOf("Osama"));           //-1
console.log(myFriends.lastIndexOf("Osama"));       //-1
```

