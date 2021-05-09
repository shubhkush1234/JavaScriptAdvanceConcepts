- "Any function that is Passed as an argument" is called callback function.

- A callback function is a function that is executed after another function has finished executing - Hence the name is callback.

- JS is an event driven language. This means that instead of waiting for a response before moving on, JS will keep executing while listening for other events.

- So, callbacks are a way to make sure certain code doesn't execute until other code has already finished execution.

```

const func1 = ( frndName, friend ) => {
    console.log(` Hi ${frndName}, I'll call you back! `);
}

const callFrnd = () => {
    console.log(`I'm callback func as I'm passes as argument, also called after func1 execution.`)
}

func1("Shubham", callFrnd);




```