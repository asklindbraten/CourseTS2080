## What is object oriented programming?

Object - oriented programming is a programming paradigm/pattern/model where software is organized in a structure of classes and objects.
This paradigm also resemblance how we organize the real world around us. For example, imagine cars as a class and different car brands as objects of the car class.  

## What are the basic concepts of OOP?

Some of the basic concepts of object - oriented programming is classes, objects, methods, inheritance, encapsulation, polymorphism and data abstraction.

Class: A class is a datatype that contains data members or member variables and/or member functions. The member functions are methods used to operate on data members. We can also consider a class as the basic blueprint for instances/objects of that class.

Object: An object is an instance of a class created with specified values stored in the attributes field. By the attributes field, I'm referring to the data members of the class. Objects also have access to the classes methods to manipulate their specific values.      


## What are the main principles of OOP?

The four main principles of object - oriented programming is encapsulation, abstraction, inheritance and polymorphism. 

## Encapsulation

Encapsulation in object - oriented programming is the process of bundling or wrapping data with the methods or functions that operate on the said data into a single unit. This is often achieved trough the use of classes.  

Why would we use encapsulation?

- Security and data hiding: Encapsulation enables the developers to prevent users or classes from directly accessing certain data members or member functions. This is normally done by declaring all variables as private and providing "getter" - functions along with other methods to view or modify the values stored in the private members. There is some key benefits to why you would do this. Not only does it reduce the risk of human error, but it makes the code management simplier and the software easier to use, without revealing all the details behind the code.

- Aesthetics and scalability: By encapsulating your code you get a particuraly appealing, structured and organized look to the design, which makes your application more manageable and intuitive. By making it easier to add methods and variables, for example, it also opens up doors for scalability. Having the opportunity to scale and increase software performance is crucial when your met with new requirements. 

## Abstraction. 

Abstraction is the process of hiding background details or implementation, and only showing the essential parts of the code. We can apply abstraction trough the use of classes and header files. Classes can decide which data members are accessible to the outside world, as mentioned earlier, while header files normally include methods that can be imported and used without knowing the actual coding - algorithm. 

Why would we use abstraction? 

Prevents code repetition and makes it easer to work in large teams: It keeps users from constantly implementing the same code every time they want to use the same algorithm. Abstraction also makes it easier for developers to work on different parts of the same project and later bundle it together, because they use the same baseline of methods or functions.     

Flexibility and security: Trough abstraction you can change background implementation without affecting the users. Showing only the essential parts of a software also increases application - security. 


## Inheritance

Inheritance is the process of creating new classes from already existing classes. These new classes are often called derived- or child classes, while the existing classes are called base- or parent classes. Derived classes inherits properties of the base class and has the ability to override said properties and add new features, without changing the actual base class. This is especially useful when it comes to  reducing data redundacy and development needs, aswell as increasing code reusability and modularity. By modularity, I am refering to the process of breaking down the codebase into smaller modules, like a derived class, for example, which makes the code easier to understand. 
## Polymorphism

Polymorphism is the process of using inherited methods from base class to perform different tasks in the derived class(es). Polymorphism is often implemented trough operator overlaoding or function overriding. Trough operator overloading you can perform operator tasks that normally wouldn't be possible without configuration. Take the "<<" operator, for example, you can overload this in a class to take an object on the right side and print all the information about the said object. Function overriding refers to the process of overriding inherited functions to perform tasks relevant to that derived class only. If we look at a base class called "Animal", with a method: "Sound()", and two derived classes called "Lion" and "Snake". We can override the "Sound()" - function in the "Lion" and "Snake" class to print the sound given by the specific animal.  
