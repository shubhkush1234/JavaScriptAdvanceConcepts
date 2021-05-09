closures in js:

- Closure in action is "inner function" can have access to the "outer function variables" as well as all the global variables.

- Closure is the combination of a "function" and "lexical environment" within which the function is declared.

- The return function didn't execute the inner function. Function is executed only when followed by (), if we wont do that, return statement will return the entire body of the function.


```

function sum (num1){
    let num2 = 20;
    return function innerFunc(){
        result = num1 + num2;
        console.log(result);
    }
}
let acbd = sum (19);
acbd();

```

