#JS_Elzero 

```js
/*
  DOM [Class List]
  - classList
  --- length
  --- contains
  --- item(index)
  --- add (tokens)
  --- remove (tokens)
  --- toggle (token)
*/

let element = document.getElementById("my-div");

console.log(element.classList);         //all the classes
console.log(typeof element.classList);  //object

console.log(element.classList.contains("osama"));   //true or false
//checks if the specified classexists in the classList of the given element

console.log(element.classList.contains("show"));
console.log(element.classList.item("3"));  //class that at index 3

element.onclick = function () {
  element.classList.add("one","two");      //add classes one , two
  element.classList.remove("one");         //remove class one 
  element.classList.toggle("show");   
  //if the class exists , it will be removed.
  //If the class doesn't exist, it will be added.
};
```
