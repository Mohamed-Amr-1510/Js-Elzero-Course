#JS_Elzero 

```js
/*
  Arrays Methods [Sort]
  - sort(Function [Opt])
  - reverse
*/

let myFriends = [10, "Sayed", "Mohamed", "90", 9000, 100, 20, "10", -20, -10];

console.log(myFriends);
//[10, "Sayed", "Mohamed", "90", 9000, 100, 20, "10", -20, -10]
console.log(myFriends.sort());
//[-10, -20, 10, "10", 100,20, "90" ,9000, "Mohamed", "Sayed"]
console.log(myFriends.sort().reverse());
//["Sayed", "Mohamed", 9000, "90", 20, 100, "10", 10, -20, -10]
```

### How Sort Works ?
It sorting the array alphabetically. ( *JavaScript compares numbers as strings.* ) 
This means : 
 - 100 comes before 20   Why ? => Because in The alphabetic 1 comes before 2.
 - 90 comes before 9000  Why ? => Because it has less zeros.


