#JS_Elzero 

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>Learn JavaScript</title>
  </head>
  <body>
    <div><!-- Osama -->Hello Div<p>Hello P</p><span>Hello Span</span><!-- Comment -->Hello</div>
    <script src="main.js"></script>
  </body>
</html>
```

```js
/*
  DOM [Deal With Childrens]
  - children
  - childNodes
  - firstChild
  - lastChild
  - firstElementChild
  - lastElementChild
*/

let myElement = document.querySelector("div");

console.log(myElement);
console.log(myElement.children);          
//all children elements (Not including text and comments)

console.log(myElement.children[0]);      //paragraph
console.log(myElement.childNodes);       
//all the nodes in the parent (including text and comments)

console.log(myElement.childNodes[0]);  //<!-- Osama -->

console.log(myElement.firstChild);   
//the first child (including text and comments)
console.log(myElement.lastChild);    
//the last child (including text and comments)

console.log(myElement.firstElementChild);   
//The first element child (Not including text and comments)
console.log(myElement.lastElementChild);
//The last element child (Not including text and comments)
```

