#JS_Elzero 

```js
/*
  Conditional (Ternary) Operator
*/

let theName = "Mona";
let theGender = "Female";
let theAge = 30;

if (theGender === "Male") {
  console.log("Mr");
} else {
  console.log("Mrs");
}

// Condition ? If True : If False

theGender === "Male" ? console.log("Mr") : console.log("Mrs");

let result = theGender === "Male" ? "Mr" : "Mrs";  
//Store the result of the condition in the variable

document.write(result);

console.log(theGender === "Male" ? "Mr" : "Mrs");

console.log(`Hello ${theGender === "Male" ? "Mr" : "Mrs"} ${theName}`);

// else if

theAge < 20
  ? console.log(20)
  : theAge > 20 && theAge < 60
  ? console.log("20 To 60")
  : theAge > 60
  ? console.log("Larger Than 60")
  : console.log("Unknown");
```

### Ternary Operator :
```js
condition ? expression_if_true : expression_if_false;
```

**Else If :**
```js
condition1 
     ? action_if_condition1_true
  : condition2 
     ? action_if_condition2_true
  : condition3 
    ? action_if_condition3_true
  : action_if_all_false;

```
