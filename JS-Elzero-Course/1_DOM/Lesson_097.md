#JS_Elzero 

```js
/*
  DOM [Deal With Elements]
  - before [Element || String]
  - after [Element || String]
  - append [Element || String]
  - prepend [Element || String]
  - remove
*/

let element = document.getElementById("my-div");
let createdP = document.createElement("p");

 element.remove();   //remove the element completely 
```


### Out of the element:

**Before:**
 ```js
 element.before(createdP); //put it before div
 ```

**After:**
 ```js
 element.after(createdP); //put it after div
 ```

### In the element:

**Append:**
 ```js
 element.append(createdP); //put it in the end of the div
 ```

**Prepend**:
 ```js
 element.prepend(createdP); //put it at the first of the div
 ```
