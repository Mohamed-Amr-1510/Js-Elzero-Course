#JS_Elzero 

```js
/*
  BOM [Browser Object Model]
  - setInterval(Function, Millseconds, Additional Params)
  - clearInterval(Identifier)
*/

// setInterval(function () {
//   console.log(`Msg`);
// }, 1000);

// setInterval(sayMsg, 1000);

// function sayMsg() {
//   console.log(`Iam Message`);
// }

// setInterval(sayMsg, 1000, "Osama", 38);

// function sayMsg(user, age) {
//   console.log(`Iam Message For ${user} His Age Is: ${age}`);
// }

let div = document.querySelector("div");

function countdown() {
  div.innerHTML -= 1;
  if (div.innerHTML === "0") {    
   // We Write "0" not 0 because it isn't a number
 
    clearInterval(counter);
  }
}

let counter = setInterval(countdown, 1000);
```

#### Note: 
- **setInterval** : it repeats a specific function with fixed time delay between every two executions.
- Time is also in **milliseconds (ms).**