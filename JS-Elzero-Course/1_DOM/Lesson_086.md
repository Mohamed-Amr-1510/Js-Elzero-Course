#JS_Elzero 

```js
/*
  DOM
  - What Is DOM
  - DOM Selectors
  --- Find Element By ID
  --- Find Element By Tag Name
  --- Find Element By Class Name
  --- Find Element By CSS Selectors
  --- Find Element By Collection
  ------ title
  ------ body
  ------ images
  ------ forms
  ------ links
*/

let myIdElement = document.getElementById("my-div");       
//Element => Because ID is unique
let myTagElements = document.getElementsByTagName("p");   
//Elements => because tag isn't unique
let myClassElement = document.getElementsByClassName("my-span");
//Elements => because class isn't unique
let myQueryElement = document.querySelector(".my-span");
//Query selector => Id,Tag,class,Any CSS selector
let myQueryAllElement = document.querySelectorAll(".my-span");

console.log(myIdElement);
console.log(myTagElements[1]);  //The second paragraph
console.log(myClassElement[1]); //The second span
console.log(myQueryElement);    
//if We have more than one with the same class as example , it will give us the first one .
console.log(myQueryAllElement);  
//It will return a list of all the elements (that has that specified class) .

console.log(myQueryAllElement[1]);

console.log(document.title);
console.log(document.body);
console.log(document.forms[0].one.value);
console.log(document.links[1].href);
```

