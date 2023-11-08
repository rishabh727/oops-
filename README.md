# oops-
**oops** - Object-oriented programming (OOP) is a computer programming model that organizes software design around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior.

1 - Class

2 - Objects

3 - Encapsulation

4 - Abstraction

5 -Polymorphism

6 -Inheritance

7 - Dynamic Binding

8 - Message Passing


![image](https://github.com/rishabh727/oops-/assets/143151167/2b3a5b41-c3a1-4f67-bd8f-5a1df5665c6d)

**class-** It is a user-defined data type, which holds its own data members and member functions, which can be accessed and used by creating an instance of that class. A Class is a user-defined data type that has data members and member functions.

**object-** An Object is an identifiable entity with some characteristics and behavior. An Object is an instance of a Class. When a class is defined, no memory is allocated but when it is instantiated (i.e. an object is created) memory is allocated.

**Encapsulation-**  In normal terms, Encapsulation is defined as wrapping up data and information under a single unit. In Object-Oriented Programming, Encapsulation is defined as binding together the data and the functions that manipulate them. 

                                           
![image](https://github.com/rishabh727/oops-/assets/143151167/e4ec9e75-a1bb-472a-934e-3d9e35645e14)

**Abstraction-**  Abstraction means displaying only essential information and hiding the details.Data abstraction refers to providing only essential information about the data to the outside world, hiding the background details or implementation. Consider a real-life example of a man driving a car. 

* Abstraction using Classes :  We can implement Abstraction in C++ using classes. The class helps us to group data members and member functions using available access specifiers. A Class can decide which data member will be visible to the outside world and which is not.

* Abstraction in Header files: One more type of abstraction in C++ can be header files. For example, consider the pow() method present in math.h header file. Whenever we need to calculate the power of a number, we simply call the function pow() present in the math.h header file and pass the numbers as arguments without knowing the underlying algorithm according to which the function is actually calculating the power of numbers

**Polymorphism-** The word polymorphism means having many forms. In simple words, we can define polymorphism as the ability of a message to be displayed in more than one form. A person at the same time can have different characteristics. A man at the same time is a father, a husband, and an employee.

**Inheritance-** The capability of a class to derive properties and characteristics from another class is called Inheritance. Inheritance is one of the most important features of Object-Oriented Programming.

* Sub Class: The class that inherits properties from another class is called Sub class or Derived Class.
  
* Super Class: The class whose properties are inherited by a sub-class is called Base Class or Superclass.
  
* Reusability: Inheritance supports the concept of “reusability”, i.e. when we want to create a new class and there is already a class that includes some of the code that we want, we can derive our new class from the existing class. By doing this, we are reusing the fields and methods of the existing class.

Example: Dog, Cat, Cow can be Derived Class of Animal Base Class. 

![image](https://github.com/rishabh727/oops-/assets/143151167/fe9c123d-6e96-4c73-8928-07f000f19573)

**Dynamic Binding**  In dynamic binding, the code to be executed in response to the function call is decided at runtime. C++ has virtual functions to support this. Because dynamic binding is flexible, it avoids the drawbacks of static binding, which connected the function call and definition at build time.

**Message Passing-**  Objects communicate with one another by sending and receiving information. A message for an object is a request for the execution of a procedure and therefore will invoke a function in the receiving object that generates the desired results. Message passing involves specifying the name of the object, the name of the function, and the information to be sent.

**mathod overloding-** In other words, we can say that Method overloading is a concept of Java in which we can create multiple methods of the same name in the same class, and all methods work in different ways.

    





