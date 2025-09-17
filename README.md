## Experiment 13 – Constructor Overloading in C++

## AIM:
    To study and implement Constructor Overloading in C++.

## APPARATUS / SOFTWARE USED:
    - Visual Studio Code (VS Code)

 ## OBJECTIVES:
    - To understand the concept of constructor overloading in C++.
    - To explore the use of default, parameterized, and copy constructors.
    - To observe how multiple constructors can coexist in a single class.
    - To analyze how constructor overloading improves flexibility, readability, 
      and reusability in object-oriented programming.


## THEORY:
    🔹 Constructor:
        A constructor in C++ is a special member function that shares the same
        name as the class and has no return type (not even void). It is invoked
        automatically whenever an object is created. The primary purpose of a 
        constructor is to initialize the data members of a class.

    🔹 Types of Constructors:
        1. Default Constructor:
            - A constructor that takes no arguments.
            - It is automatically called when an object is created without
              passing any arguments.
            - Useful for assigning default values.

        2. Parameterized Constructor:
            - A constructor that takes one or more arguments.
            - It allows passing user-defined values during object creation.
            - Helps initialize different objects with different data.

        3. Copy Constructor:
            - A constructor that creates a new object as a copy of an existing one.
            - Syntax: ClassName(const ClassName &obj).
            - Useful when objects need to be duplicated with the same values.

    🔹 Constructor Overloading:
        - C++ allows multiple constructors in the same class, provided they have
          different parameter lists (number or type of arguments).
        - The compiler identifies which constructor to invoke based on the
          arguments passed during object creation.
        - This concept is called **Constructor Overloading**.
        - It provides flexibility by enabling different ways to initialize objects.


## ALGORITHM:

    1. Start the program.
    2. Create a class "Student" with data members such as name and age.
    3. Define three constructors:
         - Default Constructor
         - Parameterized Constructor
         - Copy Constructor
    4. Create a function "display()" to show student details.
    5. In main():
         - Create an object using the default constructor.
         - Create another object using the parameterized constructor.
         - Create a third object using the copy constructor.
    6. Display the values of all objects.
    7. End the program.


## CONCLUSION:
        - Constructor overloading enables a class to define multiple constructors
          with different parameter lists.
        - It provides flexibility in object creation by allowing:
             * Default initialization
             * User-defined initialization
             * Copying values from another object
        - In this experiment, we implemented default, parameterized, and copy
          constructors for a Student class.
        - Thus, constructor overloading improves code reusability, readability,
          and provides different ways to initialize objects effectively.
    

    

