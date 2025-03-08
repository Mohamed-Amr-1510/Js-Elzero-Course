#JS_Elzero 
```js
/*
  Variables Intro
  - What Is Variable ?
  - Why We Use Variables ?
  - Declare A Variable And Use
  - Syntax ( Keyword | Variable Name | Assignment Operator | Variable Value )
  - Variable Without Var
  - Multiple Variables In The Same Line
  - Id And Global Variable
  - Loosely Typed vs Strongly Typed
*/

var user = "Sayed";
console.log(user);
```

**Variable** => named container.

#### Declare A Variable :
```js
var/*(Keyword )*/ user /*(Variable Name )*/  = /*(Assignment Operator)*/ "Sayed"/*(Variable Value)*/;
```
We don't have to write var .So We can declare a variable like that : 
```js
user ="Sayed";
```
 ( *But Watch out !!! if the variable has been declared before and you try to declare it again without var ,Overwrite will happen* ).

#### Id And Global Variable :
If We write a HTML code like that :
```html 
<div id="hello"></div>
```
There will be a global variable called hello and you can treat with it in any place in the system.

#### JS is Loosely Typed language : 
That means you don't have to mention the type of the variable when you are declaring it.

#### You must declare the variable before you start using it. 
