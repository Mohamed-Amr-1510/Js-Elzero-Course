#JS_Elzero 

```js
/*
  String Syntax + Character Escape Sequences
  \ Escape + Line Continue
  \n
*/

console.log('Elzero Web "School"');
console.log("Elzero Web 'School'");
console.log("Elzero Web \"School\"");
console.log('Elzero \\ Web \'School\'');
console.log("Elzero \
Web \
School");
console.log("Elzero\nWeb\nSchool");
```

*To Do what in the lesson you should stop the format on save : file->preferences->settings*       
*->formatonsave*

### You can write the string between single quote (') or double quote (")

### What will we do if we want to add single or double quotes in our string ?

- We can put all the string between single quotes , and the specific part between double quotes :
 ```js
 console.log('Elzero Web "School"');
 ```
 
- We can put all the string between double quotes , and the specific part between single quotes :
 ```js
 console.log("Elzero Web 'School'");
 ```

- If We Want to use the same type of quotes We will use escape character ( \\ ) :
 ```js
 console.log("Elzero Web \"School\"");
 console.log('Elzero \\ Web \'School\''); 
 /* To print the backslash(\) Write another one before it */
 ```
 
### Back slash as Line Continue :
```js
console.log("Elzero \
Web \
School"); //The sentence will be printed like that : Elzero Web School
```

### New Line :
```js
console.log("Elzero\nWeb\nSchool");
/*
The sentence will be printed like that :
Elzero
Web 
School
*/
```