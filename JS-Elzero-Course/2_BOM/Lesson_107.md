#JS_Elzero 

```js
/*
  BOM [Browser Object Model]
  - open(URL [Opt], Window Name Or Target Attr [Opt], Win Features [Opt], History Replace [Opt])
  - close() 
  - Window Features
  --- left [Num]
  --- top [Num]
  --- width [Num]
  --- height [Num]
  --- menubar [yes || no]

  Search
  - Window.Open Window Features
*/

setTimeout(function () {
  window.open("", "_self", "", false);
}, 2000);

setTimeout(function () {
  window.open("https://google.com", "_blank", "width=400,height=400,left=200,top=10");
}, 2000);
```

#### Notes :
- **close()** => closes the window that opened with JS ( `window .open()` ).
- **Window Name** *(that We write in `open()`)* :  doesn't affect page's title. It is only an identifier.
- The Default Target Attribute is \_blank .
- 