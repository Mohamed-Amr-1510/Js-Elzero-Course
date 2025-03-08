#JS_Elzero 

```js
/*
  DOM [Events Simulation]
  - click
  - focus
  - blur
*/

let one = document.querySelector(".one");
let two = document.querySelector(".two");

window.onload = function () {
  two.focus();         
  //When the page loaded, automatically there will be focus on element two
};

one.onblur = function () {
  document.links[0].click();
  //When I blur the element one , click on the link automatically.
};
```

