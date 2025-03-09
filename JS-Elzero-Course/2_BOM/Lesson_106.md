#JS_Elzero 

```js
/*
  BOM [Browser Object Model]
  - location Object
  --- href Get / Set [URL || Hash || File || Mail]
  --- host
  --- hash
  --- protocol
  --- reload()
  --- replace()
  --- assign()
*/

console.log(location);
console.log(location.href);

// location.href = "https://google.com";
// location.href = "/#sec02";
// location.href = "https://developer.mozilla.org/en-US/docs/Web/JavaScript#reference";

// console.log(location.host);        your site name + port
// console.log(location.hostname);    your site name only

// console.log(location.protocol);

// console.log(location.hash);
```

#### Notes :

- **Location object** : Has methods and properties for your URL.
- When we use `location.href` to go to new URL, the browser navigates to that URL without deleting the current page from the  history.
- **location.host** => gives you your site name + port.
- **location.hostname** => gives you your site name only.
- **replace( URL )**   =>  Removes the current page from the session history.
- **assign( URL )**     =>  doesn't remove the current page from the session history.
