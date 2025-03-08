#JS_Elzero 

```js
/*
  DOM [Cloning]
  - cloneNode(Deep)
*/

let myP = document.querySelector("p").cloneNode(true); 
//take a copy of the element with its attributes .
//myP will refer to the copied element.
let myDiv = document.querySelector("div");

myP.id = `${myP.id}-clone`;  //change the copied element id.

myDiv.appendChild(myP);
```


**Notes** :
 ```js
 cloneNode(true);    // Copy the child elements also

 cloneNode(false);  //Copy the element without its children.
 cloneNode();      // Copy the element without its children.
 ```

