Higher order functions are functions that take other functions as arguments OR returns functions as their result.

eg:

```

const interviewQuestions = (name) => {
    if(name == "Shubham"){
        return function(topic){
            console.log("Hi ${name} , What is ${topic} ?");

        }
    };
    if(name == "Saumya"){
        return function(topic){
            console.log("Hi ${name} , What is ${topic} ?");

        }
    }
    if(name == "Venkat"){
        return function(topic){
            console.log("Hi ${name} , What is ${topic} ?");

        }
    }
    else{
        return function(){ console.log("welcome to interview");
    }
    
}

interviewQuestions("Shubham")("JS");
interviewQuestions("Venkat")("JQuery");


```