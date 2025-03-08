#JS_Elzero 

If We put the JS code in an external file like that :
 ```html
    <script src="main.js"></script>
```

So We must Take order into consideration.

## The difference :
```html
That will give me error (If I want to put JS code related to h1 in main.js).

  <script src="main.js"></script>
  <h1>Page</h1>
```


```html
That is the right code

  <h1>Page</h1>
  <script src="main.js"></script>
```

So It is recommended to put the <script></script> in the end of the file <span style="background:#b1ffff">(The best Practice)</span>.

We can skip that problem by using :
  ```js
  window.onload = function{
  
  }
  ```
