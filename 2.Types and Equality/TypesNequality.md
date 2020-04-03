# Types and Equalities in JS: #

What are different types in JS?

1. Primitive types:
    Boolean // true, false
    Number  // 1, 2.3, 444.233
    String  // "Shubham", "Shubham Kushwaha"
    Null    // null
    Undefined   //undefined

2. Non-primitive types:

    Object  // {}, new Object()

The method typeOf():
It checks the type of a value.

```js
    typeof(true)
    "boolean"

    typeof(1)
    "number"

    typeof("abcd")
    "string"

    typeof(null)
    "object"

    typeof(undefined)
    "undefined"

    typeof([])
    "object"

    typeof({})
    "object"
```
In JS, it seems there are seemingly 2 redundent ways to represent the concept of no value: null and undefined.

But there is actually a subtle difference between the two. 

var a;
console.log(a);
//undefiend

<b>Undefined</b> is used by javascript to define the unknown value or uninitialized value, unknown variable, unknown function arguments and unknown properties.

Eg:
```js
var a;
undefined
window.shubham
undefined
```
<img src="TypesNequality1.png" alt="TypesNequality1.png screenshot"/>
So, undefined is a core js function uswd by js engine to inform you that if it's an uninitialized variable or unknown property of object or parameter missing from parameter's list or something whose value is not set. 






























