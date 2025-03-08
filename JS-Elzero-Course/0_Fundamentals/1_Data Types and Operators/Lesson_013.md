#JS_Elzero 

```js
/*
  Var
  - Redeclare (Yes)
  - Access Before Declare (Undefined)
  - Variable Scope Drama [Added To Window] ()
  - Block Or Scope Function

  Let
  - Redeclare (No => Error)
  - Access Before Declare (Error)
  - Variable Scope Drama ()
  - Block Or Scope Function

  Const
  - Redeclare (No => Error)
  - Access Before Declare (Error)
  - Variable Scope Drama ()
  - Block Or Scope Function
*/
```

## Var :
  
  - Redeclare ( Yes )
  - Access Before Declare  ( Undefined => No Error)
  - Variable Scope Drama ( Added To Window )
    *If you declare a variable using `var` outside any function, it automatically becomes a part of the window object, meaning you can access it through `window.variableName`.*
  - Block Or Scope Function

## Let :
  
   - Redeclare  ( No => Error )
  - Access Before Declare ( Error )
  - Variable Scope Drama (Won't be Added To Window)
  - Block Or Scope Function
## Const :
  
  - Redeclare ( No => Error )
  - Access Before Declare ( Error )
  - Variable Scope Drama ( Won't be Added To Window )
  - Block Or Scope Function
