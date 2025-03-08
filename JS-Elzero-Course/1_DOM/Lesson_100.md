#JS_Elzero 

```js
/*
  DOM [Add Event Listener]
  - addEventListener
  - Use Without On
  - Attach Multiple Events
  - Error Test

  Search
  - Capture & Bubbling JavaScript
  - removeEventListener
*/

let myP = document.querySelector("p");

// myP.onclick = one;
// myP.onclick = two;

// function one() {
//   console.log("Message From OnClick 1");
// }
// function two() {
//   console.log("Message From OnClick 2");
// }

// window.onload = "Osama";    =>    NoError (without the evenrlistener)

// myP.addEventListener("click", function () {
//   console.log("Message From OnClick 1 Event");
// });

// myP.addEventListener("click", one);
// myP.addEventListener("click", two);

// myP.addEventListener("click", "String");                   //  Error

myP.onclick = function () {                
//When YOu click the paragraph , create a clone paragraph
  let newP = myP.cloneNode(true);
  newP.className = "clone";
  document.body.appendChild(newP);
};

// let cloned = document.querySelector(".clone");            // Error
/* 
The Error because cloned isn't created in the page yet
*/

// cloned.onclick = function () {
//   console.log("Iam Cloned");
// };

document.addEventListener("click", function (e) {
  if (e.target.className === "clone") {
    console.log("Iam Cloned");
  }
});
```

#### The First Method:
```js
let myP = document.querySelector("p");

 myP.onclick = one;
 myP.onclick = two;

 function one() {
   console.log("Message From OnClick 1");
    }
function two() {
   console.log("Message From OnClick 2");
 } 

// Output => Message From OnClick 2 (Because function two overwrites function one)
```

#### Event Listener with anonymous function :
```js
myP.addEventListener("click", function () {
 console.log("Message From OnClick 1 Event");
});
```

#### Event Listener with usual function :
```js
myP.addEventListener("click", one);
myP.addEventListener("click", two);

/*
Output => 
Message From OnClick 1 
Message From OnClick 2
*/
```