#JS_Elzero 

```js
/*
  DOM [CSS]
  - style
  - cssText
  - removeProperty(propertyName) [Inline, Stylesheet]
  - setProperty(propertyName, value, priority)
*/

let element = document.getElementById("my-div");

element.style.color = "red";
element.style.fontWeight = "bold";   
//Any property that consists of more than one word , use camel case with it

element.style.cssText = "font-weight: bold; color: green; opacity: 0.9";
//To write more than one property together.
//We write properties here as we write in CSS.

element.style.removeProperty("color");     
//removes property from the **inline style**
element.style.setProperty("font-size", "40px", "important");

document.styleSheets[0].rules[0].style.removeProperty("line-height");
//removes the property from a CSS rule in a stylesheet.
document.styleSheets[0].rules[0].style.setProperty("background-color", "red", "important");
```

