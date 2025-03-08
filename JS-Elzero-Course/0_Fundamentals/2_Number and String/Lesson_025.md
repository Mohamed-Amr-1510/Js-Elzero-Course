#JS_Elzero 
```js
/*
  Math Object
  - round()
  - ceil()
  - floor()
  - min()
  - max()
  - pow()
  - random()
  - trunc() [Es6]
*/

console.log(Math.round(99.2));
console.log(Math.round(99.5));

console.log(Math.ceil(99.2));
console.log(Math.floor(99.9));

console.log(Math.min(10, 20, 100, -100, 90));  //-100
console.log(Math.max(10, 20, 100, -100, 90));  //100

console.log(Math.pow(2, 4));  //2*2*2*2
console.log(Math.random());
console.log(Math.trunc(99.5));  //99
```

#### Round:
if The number is  X.a and a>=5 So :
 ```js
 console.log(Math.round(X.a));  // X+1 
 ```
if The number is  X.a and a<5 So :
 ```js
 console.log(Math.round(X.a));  // X 
 ```

#### Ceil:
if The number is  X.a  (to the higher):
 ```js
 console.log(Math.ceil(X.a));  // X+1 (only in the case of X >=0) 
 ```

#### Floor:
if The number is  X.a (to the lower)  :
 ```js
 console.log(Math.floor(X.a));  // X   (only in the case of X >=0) 
 ```
#### Trunc:
if The number is  X.a  (return the integer part.) :
 ```js
 console.log(Math.trunc(X.a));  // X 
 ```


### So What is the difference between floor and trunc :

The Difference will appear in the negative valuse :
```js
console.log(Math.floor(-9.5)); //-10
 console.log(Math.trunc(-9.5)); //-9
```