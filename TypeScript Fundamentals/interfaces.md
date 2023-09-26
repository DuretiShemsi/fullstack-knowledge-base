## Working with Interfaces video

## TypeScript allows you to implement interfaces in classes, ensuring that a class adheres to a specific contract. This is especially useful when defining a contract that multiple classes 

## can be implemented by classes and forse the class to have the interface that is defined

interface Human {
    firstName: string;
    age: numebr;

    greet: () => void;
}

let max : Human;

max ={
    firstName : 'Max',
    age: 32,

    greet (){
        console.log ('Hello');
    },
};

class Instructor implements Human {
    firstName: string;
    age: numebr;

    greet (){
        console.log ('Hello!!!');
    }
}