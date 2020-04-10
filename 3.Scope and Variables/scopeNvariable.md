# Scope and Variable #

<h3>What are different scope in JS?</h3>

1. Global scope
2. Function scope
3. Block scope

<img src="scopeNvariable.png" alt="scopeNvariable.png screenshot"/>

1. Global scope:

Global variables are availabe throghout the application.

All the global variables are the properties of the window object.

2. Function scope:

<img src="scopeNvariable.png" alt="scopeNvariable.png screenshot"/>

Java and Python coders will think that it's having block scope. So, to demonstrate it, lets try out an example:

<img src="scopeNvariable1.png" alt="scopeNvariable1.png screenshot"/>

```js
    "use strict";

    for (var i = 0; i < 9; i++) {
        var j = 7;
    }
    console.log(j);
```

loops are having global scope and hence i and j are also having the global scope as well. 



















