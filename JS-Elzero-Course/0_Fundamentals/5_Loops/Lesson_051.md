#JS_Elzero 

```js
/*
  Loop Control
  - Break
  - Continue
  - Label
*/

let products = ["Keyboard", "Mouse", "Pen", "Pad", "Monitor"];

let colors = ["Red", "Green", "Black"];

mainLoop: for (let i = 0; i < products.length; i++) {  //Label
  console.log(products[i]);
  nestedLoop: for (let j = 0; j < colors.length; j++) {
    console.log(`- ${colors[j]}`);
    if (colors[j] === "Green") {
      break mainLoop;        
      //It breaks the main loop so It gets out of the 2 loops         
    }
  }
}
```

**Break**      =>  It gets out of the loop.
**Continue** => It skips only the case you determine but completes the loop.
**Label**       => Identifier for the loop.