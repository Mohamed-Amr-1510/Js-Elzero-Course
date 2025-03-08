#JS_Elzero 

```js
/*
  DOM [Get / Set Elements Content And Attributes]
  - innerHTML
  - textContent
  - Change Attributes Directly
  - Change Attributes With Methods
  --- getAttribute
  --- setAttribute

  Search
  - innerText
*/

let myElement = document.querySelector(".js");

console.log(myElement.innerHTML);    //Returns Html
console.log(myElement.textContent);  //Returns text 

myElement.innerHTML = "Text From <span>Main.js</span> File";
//span will be added as html
myElement.textContent = "Text From <span>Main.js</span> File";
//span will be added as a text

document.images[0].src = "https://google.com";
document.images[0].alt = "Alternate";
document.images[0].title = "Picture";
document.images[0].id = "pic";
document.images[0].className = "img";
//If the attribute already Exists, its value will be overwritten.
//If If the attribute doesn't Exist.It will be added.

let myLink = document.querySelector(".link");

console.log(myLink.getAttribute("class"));   //class value
console.log(myLink.getAttribute("href"));   //href value

myLink.setAttribute("href", "https://twitter.com");   
//changes href value to https://twitter.com
myLink.setAttribute("title", "Twitter");
//changes title value to Twitter
```