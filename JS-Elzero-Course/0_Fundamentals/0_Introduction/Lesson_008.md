#JS_Elzero 

```js
/*
  Console Methods
  - log
  - error
  - table

  Web API

  Styling Console
  - Directive %c
*/

console.log("Log");
console.error("Error");
console.table(["Osama", "Ahmed", "Sayed"]);

console.log("Hello From %cJS %cFile", "color: red; font-size: 40px", "color: blue; font-size: 40px");
```

#### Console has a lot of built-in functions : 
 We can print the message in the console as an error by :
  ```js
  console.error()
  ```

 We can print the message in the console as an array by :
  ```js
  console.table(["Osama", "Ahmed", "Sayed"]);
  ```

 We can print the message in the console with some styling by : **(using Directive %c)**
  ```js
  console.log("Hello From %cJS File", "color: red; font-size: 40px");
  ```
  We can use it more than one time  : 
   ```js
   console.log("Hello From %cJS %cFile", "color: red; font-size: 40px"/*for the first directive*/, "color:blue; font-size: 40px"/*for the second directive*/);
   ```
  
#### Console isn't belonging to JS but to Web API.
 