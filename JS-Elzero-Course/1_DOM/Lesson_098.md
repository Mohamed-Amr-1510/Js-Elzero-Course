#JS_Elzero 

```js
/*
  DOM [Traversing]
  - nextSibling             => The next sibling
  - previousSibling      
  - nextElementSibling     => The next elemnt sibling (ignoring any thing except element)
  
  - previousElementSibling
  - parentElement            => to raech any chlid parent
*/

let span = document.querySelector(".two");

console.log(span.parentElement);

span.onclick = function () {
  span.parentElement.remove();    
}
```

