#JS_Elzero 

```js
/*
  BOM [Browser Object Model]
  - setTimeout(Function, Timeout, Additional Params)
  - clearTimeout(Identifier)
*/

// setTimeout(function () {
//   console.log("Msg");
// }, 3000);

// setTimeout(sayMsg, 3000);

// function sayMsg() {
//   console.log(`Iam Message`);
// }

// setTimeout(sayMsg, 3000, "Osama", 38);

// function sayMsg(user, age) {
//   console.log(`Iam Message For ${user} Age Is : ${age}`);
// }

let btn = document.querySelector("button");

btn.onclick = function () {
  clearTimeout(counter);
};

function sayMsg(user, age) {
  console.log(`Iam Message For ${user} Age Is : ${age}`);
}

let counter = setTimeout(sayMsg, 3000, "Osama", 38);
//counter is like an ID for the setTimeout
```

#### Note :
- **setTimeout**  : This is a function that lets you set a timer to run a specific task after a certain amount of time.
- The time you write in time function is in **milliseconds (ms)**.


```js

setTimeout(sayMsg("Osama", 38), 3000) 
//If We pass them like that the setTimeout function won't work

 setTimeout(sayMsg, 3000, "Osama", 38); // To add arguments 


 function sayMsg(user, age) {
   console.log(`Iam Message For ${user} Age Is : ${age}`);
 }
```

- **clearTimeout** : Stops the time out. (  *stops the scheduled task from running if it hasn't already executed.* )