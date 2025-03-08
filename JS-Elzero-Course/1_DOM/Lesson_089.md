#JS_Elzero 

```js
/*
  DOM [Create Elements]
  - createElement
  - createComment
  - createTextNode
  - createAttribute
  - appendChild
*/

let myElement = document.createElement("div");
let myAttr = document.createAttribute("data-custom");
let myText = document.createTextNode("Product One");
//Create empty text
let myComment = document.createComment("This Is Div");

myElement.className = "product";
myElement.setAttributeNode(myAttr);
//Give them an attribute that created and you will modify it later.

myElement.setAttribute("data-test", "Testing");
//Creating Attribute and give it the value.


// Append Comment To Element
myElement.appendChild(myComment);

// Append Text To Element
myElement.appendChild(myText);

// Append Element To Body
document.body.appendChild(myElement);
```


### Differences :
```js
myElement.className = "product"; 
```
1. We Use it to modify an already Existing attribute.
2. It doesn't create any attribute.

```js
let myAttr = document.createAttribute("data-custom");
myElement.setAttributeNode(myAttr);
```
1. Creates an attribute.
2. Attaches it to myElement.
3. The attribute still doesn't have value. So, you can add it later.

```js
myElement.setAttribute("data-test", "Testing");
```
1. If The attribute doesn't exist, the code will create the Attribute and give it the value.
2. If the attribute already exists, the code will update its value with the new one.