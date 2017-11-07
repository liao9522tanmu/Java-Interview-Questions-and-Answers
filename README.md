## Java Interview Questions and Answers
### Object-Oriented Programming
* What are the main 3 Object Oriented Programing (OOP) concepts?
* Explain object serialization and how to implement it in Java.
* Explain anonymous classes. 
* Describe the differences between abstract classes and interfaces. 
* Explain what a Singleton class is and how to create one in Java 
* Why should the equals() and hashCode() methods often be overridden together? 
* How do you properly override the equals() method? For example, what considerations should be taken when checking for equality?
* Difference between final, finally and finalize?
* In Java, does the finally block gets executed if we insert a return statement inside the try block of a try-catch-finally?
* Explain method overloading & overriding. 
* What is memory leak and how does Java handle it?

### Constructor
* What is constructor?
> Constructor is just like a method that is used to initialize the state of an object. It is invoked at the time of object creation.
* What is the purpose of default constructor?
> The default constructor provides the default values to the objects. The java compiler creates a default constructor only if there is no constructor in the class.
* Does constructor return any value?
> Yes, that is current instance (You cannot use return type yet it returns a value).
* Is constructor inherited?
> No, constructor is not inherited.
* Can you make a constructor final?
> No, constructor can't be final.

### static
* What is static variable?
> static variable is used to refer the common property of all objects (that is not unique for each object) e.g. company name of employees,college name of students etc.
> static variable gets memory only once in class area at the time of class loading.

* What is static method?
> A static method belongs to the class rather than object of a class.
A static method can be invoked without the need for creating an instance of a class.
static method can access static data member and can change the value of it.

### Interesting
* What is the default value of the local variables?
> The local variables are not initialized to any default value, neither primitives nor object references.
