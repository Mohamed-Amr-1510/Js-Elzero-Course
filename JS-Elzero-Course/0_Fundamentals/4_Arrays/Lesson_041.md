#JS_Elzero 

```js
/*
  Array Methods
  - Length
*/

// Index Start From 0 [ 0, 1, 2, 3, 4 ]

let myFriends = ["Ahmed", "Mohamed", "Sayed", "Alaa"];

myFriends.length = 2;  

console.log(myFriends);       //["Ahmed", "Mohamed"]
```

### Notes :
1. 
 ```js
 let myFriends = ["Ahmed", "Mohamed", "Sayed", "Alaa"];

 myFriends[6] = "Gamal";

 console.log(myFriends);  //[ 'Ahmed', 'Mohamed', 'Sayed', 'Alaa', empty × 2,  'Gamal']
 console.log(myFriends.length); //7
 ```

2. Length = Index+1
3. To Add new element in the end of the array:
 ```js
 let myFriends = ["Ahmed", "Mohamed", "Sayed", "Alaa"];
 
 myFriends[myFriends.length] = "Gamal";

 console.log(myFriends); // [ 'Ahmed', 'Mohamed', 'Sayed', 'Alaa', 'Gamal' ]
 ```
4. Always Update the last element:
 ```js
  let myFriends = ["Ahmed", "Mohamed", "Sayed", "Alaa"];
 
 myFriends[myFriends.length - 1] = "Gamal";

 console.log(myFriends);  //[ 'Ahmed', 'Mohamed', 'Sayed', 'Gamal' ]

 ```
 