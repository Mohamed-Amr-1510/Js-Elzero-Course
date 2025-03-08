#JS_Elzero 

```js
/*
  DOM [Events]
  - Use Events On HTML
  - Use Events On JS
  --- onclick
  --- oncontextmenu   => right click
  --- onmouseenter    => When mouse touch the element
  --- onmouseleave    => When mouse touch and leave the element

  --- onload
  --- onscroll       => while scrolling the page
  --- onresize       => when you resize the window

  --- onfocus        => when you focus on the element.
  --- onblur         => when you leave the element and get out the focus.
  --- onsubmit       => When you submit the form.
*/

let myBtn = document.getElementById("btn");

myBtn.onclick = function () {
  console.log("Clicked");
};

myBtn.onmouseleave = function () {
  console.log("Clicked");
};

window.onresize = function () {
  console.log("Scroll");
};
```

You can use events in the html code like that :
 ```html
 <button onclick="console.log('Clicked')">Button</button>
 ```