#JS_Elzero 

```js
/*
  Loop For Advanced Example
*/

let products = ["Keyboard", "Mouse", "Pen", "Pad", "Monitor", "iPhone"];
let i = 0;

for (;;) {
  console.log(products[i]);
  i++;
  if (i === products.length) break;
}
```


### Notes :
- If We Write the loop like `for(i=0;;)` .So We can't access  i outside the loop.