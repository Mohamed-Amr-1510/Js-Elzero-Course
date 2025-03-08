#JS_Elzero 
```js
/*
  Template Literals (Template Strings)
*/

// First Example

let a = "We Love";
let b = "JavaScript";
let c = "And";
let d = "Programming";

console.log(a = " \"\" " + b +
"\n" + c + " " + d);

console.log(`${a} "" '' \\ ${b}
${c} ${d}`);

// Second Example

let title = "Elzero";
let desc = "Elzero Web School";

let markup = `
  <div class="card">
    <div class="child">
      <h2>${title}</h2>
      <p>${desc}</p>
    </div>
  </div>
`;

document.write(markup);
```

### (In ES6+)
- To add any variable : We will use ${ variable name } 
- We will put all the string between backtick ( \` \` )
- No Escaping Characters.


### Difference Between legacy code and Template Literals :
![Image](https://github.com/user-attachments/assets/16fd3ee8-f930-4668-9dd0-65f34e6844e5)
