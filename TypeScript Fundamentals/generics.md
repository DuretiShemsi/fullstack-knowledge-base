## Understanding Generics video

##  Allow you to create functions, classes, and interfaces that can work with different data types without sacrificing type checking. Generics enable you to write code that is more generic or abstract, thus reducing code duplication and improving code maintainability.


function insertAtBeginning <T>(array: T[], value: T){
    const newArray = [value,...array];
    return newArray;
}

const demoArray = [1,2,3];

const updatedArray = insertAtBeginning (demoArray, -1); //[-1,1,2,3]
const stringArray = insertAtBeginning(['a','b','c'])

//updatedArray[0].split('');