The context of this in a browser in global scope is <b>Window</b> object.

```js
    console.log(this);

    this.shubham = 25;
        
    console.log(this.shubham);//25
    console.log(window.shubham);//25
    console.log(shubham);//25
```

So, from the above example, we come to a conclusion that <b>this</b> points to the global (window) object.

Lets try it out in a function.

```js

    function checkThis() {
        console.log(this);
    }
    checkThis();
```
It also console logs the global window object. Till now we can conclude that this always refers to global (window) object, but that's not true. 

```js 

    var shubham = {
        checkThis : function() {
            console.log(this);
        }
    }
    shubham.checkThis();
    console.log(shubham);
```
<img src="This1.png" alt="This1.png screenshot"/>

Here, the this keyword is pointing to the object "shubham".
To prove this, lets console log this object as well.

<img src="This2.png" alt="This2.png screenshot"/>

Yes, confirmed, it's exact same!

So, till now we can conclude that "this" refers to the object the function is declared on. 


```js 

    var shubham = {
        checkThis : function() {
            console.log(this);
        }
    }
    
    //shubham.checkThis();
    //console.log(shubham);
    var func = shubham.checkThis;
    func();

```
Again, this is referring to the global window object.

In JS, "this" is determined by the calling context. It is determined by the way in which function is called.








































