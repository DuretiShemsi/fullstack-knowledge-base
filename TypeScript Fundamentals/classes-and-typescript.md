## Classes and Typescript Video

## TypeScript supports access modifiers like public, private, and protected. These modifiers control the visibility and accessibility of class members (properties and methods)


class student {
    firstName: string;
    lastName: string;
    age: number;
    private courses: string[];

    constructor(first: string, last: string, age: number, courses: string[]){
        this.firstName = first;
        this.lastName = last;
        this.age = age;
        this.course = courses;
    }
    enroll(courseName: string){
        this.courses.push(courseName);
    }

    listCourses(){
        return.this.courses.slice();
    }
}

const student = newStudent('Max','Kevin',32,['Angular']);
student.enroll('React');

// student.courses => Angular, React b