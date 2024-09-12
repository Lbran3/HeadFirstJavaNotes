Chapter 2,3,4 Head First Java Notes

•	Object: An instance of a class with its own state and behavior.
•	Class: A template for creating objects.
•	Encapsulation: Keeping data safe from external access by using access control.
•	Primitives: Basic data types like Boolean, char, etc.
•	Reference Variables: Store addresses to objects in memory.
•	Arrays: Object that stores multiple values of the same type.
•	Method Overloading: Defining multiple methods with the same name but different parameters.
•	This Keyword: Refers to the current instance of a class.
•	Instance Variables: Hold the state of the object.
•	Methods: Represent the object’s behavior.
Encapsulation:
•	Combining data (variables) and methods into a single unit ex: (the object)
•	Protects the state of the object by restricting direct access to instance variables (typically w/ private access modifiers).
Dot Operator:
Used to access an object’s variables and methods:
•	Objects are stored in the heap, and local variables (e.g., references) are stored in the stack.

•	Primitive Data Types: Built-in data types in Java (int, char, Boolean, etc) They hold a value.

•	Reference Variables: Store the address (reference) of an object in memory, not the actual object itself.

Default Values:
•	Primitives have default values (e.g., int defaults to 0).
•	Reference variables default to null when uninitialized.
Arrays:
•	Arrays are objects in Java that store multiple values of the same type.
•	Java automatically reclaims memory used by objects that are no longer referenced, freeing the heap space.

Pass-by-Value:
•	Java passes a copy of the variable, not the actual variable itself. For primitives, it's the value itself; for objects, it's the reference to the object.

Method Basics:
•	Methods define the behavior of an object.
•	A method can return a value or void if it doesn’t return anything.

Passing Parameters:
•	Methods can take parameters (inputs) to operate on.
Getters and Setters:
•	Getter: A method that returns the value of an instance variable.
•	Setter: A method that updates the value of an instance variable.
Method Overloading:
•	Having multiple methods with the same name but different parameter lists 
Variables:
•	-Variables must have a type
•	-Variable must have a name
•	-A variable is just a cup, container. It holds something

•	You can assign a value to a variable in the one of several ways including:
•	-type literal value after the equal sign (isReal=true, y=26, etc)
•	-assign the value of one variable to another (x=y)
•	-use an expression combining two (x= y + 43
