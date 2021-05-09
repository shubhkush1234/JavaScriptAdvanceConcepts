## Destructuring ##


#### Object Destructuring  ###

- Destructuring is basically a eau of extracting values into variables from data storing objects or arrays.

```javaScript

const obj = {first: "Shubham", last: "Kushwaha", age: 25};

const f = obj.first
const l = obj.last

console.log(f);
console.log(l);

```

The destructuring syntax of js is:

```javaScript

const obj = {first: "Shubham", last: "Kushwaha", age: 25};


const { first: f, last: l } = obj;

console.log(f); // shubham
console.log(l); // Kushwaha

// const f = obj.first
// const l = obj.last

```

Also, we can detructure a object property by declaring the same variable name as well:

```javaScript

const obj = {first: "Shubham", last: "Kushwaha", age: 25};


const { first: first, last: last } = obj;

console.log(first); // shubham
console.log(last); // Kushwaha

// const f = obj.first
// const l = obj.last

```

The shorthand syntax for declaring the same name property and variable name is:

```javaScript

const obj = {first: "Shubham", last: "Kushwaha", age: 25};


const { first, last } = obj;

console.log(first); // shubham
console.log(last); // Kushwaha

// const f = obj.first
// const l = obj.last

```


#### Array Destructuring  ###


```javaScript

const obj = ["Shubham", "Kushwaha", 25];


const { first, last } = obj;

console.log(first); // shubham
console.log(last); // Kushwaha

// const f = obj.first
// const l = obj.last

```

### For Loops ###

```javaScript

























