# C++
Back To
[Home Page](https://github.com/nasz8f/4330-7330_Final_Project/blob/master/README.md)


### Language Purpose:
  * C++ was designed by Bjarne Stroustup. He wanted to create a C like language with more features introduced in higher level languages. He created "C with classes" until 1983 when the name was changed to c++
  * the bigest issue Stroustup had with c was adding data abstraction and also creating an object oriented language. Another issue he had with c was distributing operating system facilities across a network.

_____________________________________________________________________________________________________________________________________________

### Features:
 * Encapsulation
 
 * Abstraction
 
 * Polymorphism
 
 * Inheritance

_____________________________________________________________________________________________________________________________________________

### Name Spaces:
 * In C++ namespaces are declared at the beginning of a program using the keyword 'namespace' followed by a custom name for the namespace.  This allows you to create your own namespace instead of using a default one.  This is very similar to the second way namespaces are implemented in C#.
 
 * In C++ namespaces encapsulate each version of an interface nested inside the parent, which is the namespace.

_____________________________________________________________________________________________________________________________________________

### Types:
 * unsigned char
   
   char
   
   char16_t
   
   char32_t
   
   wchar_t
   
   unsigned short
   
   short
   
   unsigned int
   
   int
   
   unsigned long
   
   long
   
   unsigned long long
   
   long long
   
   float
   
   double
   
   long double
   
   bool
   
   void
   
   decltype(nullptr)
   
 * C++ does support both value and reference types.
 
 * New value types can be created in C++. With user-defined types, you can use new to invoke the default constructor.

_____________________________________________________________________________________________________________________________________________

### Classes:
 * A class can be defined choosing an access level such as publuc, private, protected, or default. This is followed by the keyword 'class' and then the custom name of your class.

* A new object, or instance, can be created in a class by using the 'new' keyword, followed by the name of the class that the instance is based on.

* When initializing a class, its constructor is called. To create a class's constructor an access level must be chosen, followed by the keyword 'class' since the constructor shares the same name as the class and it's custom name. This is to be created somewhere above the class that uses it. The class can then be instantiated using the constructor by using the keyword 'new'.
 
* In C++ a class may only have one deconstructor which can't be called. A deconstructor is invoked automatically. It doesn't hve modifiers or parameters. A deconstructor may be created by calling the keyword 'class' with the class's custom name. Inside of the brackets of this, the name of the class preceded by a '~' and followed by '()'. This will deconstruct a class.
 ____________________________________________________________________________________________________________________________________________

### Instance Reference in Data Type:
* C++ supports both this and self.  'this' is a keyword while 'self' is a variable.  'This' always refers to the object that is executing a particular method.  'self' variables may be modified during execution.  For example, A constructor may assign a 'self' variable to nil on failure.
 
 ____________________________________________________________________________________________________________________________________________

### Properties:
 * In C++ getters and setters are not built in, you must write your own.
 
 * Backing variables do exist in C++.
 
 * Computed properties do not exist in C++
 
  ____________________________________________________________________________________________________________________________________________


### Interfaces/Protocals:
 * C++ implements interfaces as abstract classes. The 'interface' keyword includes behavior from multiple sources in a class.
 
 * An abstract class provides a base class which other classes can inherit from.
 
 * An abstract class is used by calling a function from a base class using the interface.
 
  ____________________________________________________________________________________________________________________________________________


### Inheritance/Extension:
 C++ Supports multiple inheritance. This is unusual as most Object Oriented Languages do not, b/c multiple inheritance is hard to maintain and is "Error prone". C++ also supports extension.
 
  ____________________________________________________________________________________________________________________________________________


### Reflection:
 C++ does not support Reflection.
 
 Reflection is useful in the following situations: When you have to access attributes in your program's metadata. For examining and instantiating types in an assembly. For building new types at runtime. For performing late binding, accessing methods on types created at run time
  ____________________________________________________________________________________________________________________________________________


### Memory Management:
 C++ supports automatic memory management via garbage collection and RAII. C++ also takes advantage of Smart Pointers
 
A smart pointer type is defined as any class type that overloads operator->, operator*, or operator->*. One thing to note straight away is that "smart pointers" are, in a sense, not really pointers at all -- but overloading these operators allows a smart pointer to behave much like a built-in pointer, and much code can be written which works with both "real" pointers and smart pointers.

C++ also offers manual memory management. This can be implemented with the use of "new" and "delete". however it is noted that these functions are rarely used as there are more sophisticated formed of handling memory given to the language.
 
  ____________________________________________________________________________________________________________________________________________


### Comparisons of Reference and Values:
  * In C++ strings can be compared in two ways.  First, strings can be compared if one assigns a string to a string variable and use the '==' operator to see if the string is equal to a string value which would be typed in quotation marks.  This can be implemented in something such as an if statement.  Another way of comparing strings is to use the built in operator "compare".  It can be implemented by first assigning two strings to two different variables.  They can be compared by typing the name of the first string, followed by a ".", followed by "compare()".  In the parenthesis the name of the second string is to be stated.  This operator will return an integer.  If "0" is returned, the strings are equal.  If the value returned is positive, the compared string is either longer or it's first non-matching character is of greater value.  If the value returned is negative, the compared string is either shorter or it's first non-matching character is of lesser value.
  ____________________________________________________________________________________________________________________________________________


### Null References:
 c++ does use null. 
 However Null can be used to initalize to 0. This is a value that can be silently converted to pointer.
 
  ____________________________________________________________________________________________________________________________________________


### Errors and Exception Handling:
 [Information Here]
 
  ____________________________________________________________________________________________________________________________________________


### Lambda Expressions/Closures/Functions as Types:
 A lambda expression in C++ are functions that are used to define the function at the location it is called. There is normally an encapsulation of a few lines of code that are considered and passed as an algorithms or asynchronous method. They are used just to clarify what will be happening in the lines, and use nearby values when needed
 
  ____________________________________________________________________________________________________________________________________________


### Implementation of Listeners and Event Handlers:
##### Declaring Events

In an event source class, use the \_\_event keyword on a method declaration to declare the method as an event. Make sure to declare the method, but do not define it; to do so will generate a compiler error, because the compiler defines the method implicitly when it is made into an event.


##### Defining Event Handlers

In an event receiver class, you define event handlers, which are methods with signatures (return types, calling conventions, and arguments) that match the event that they will handle.


##### Hooking Event Handlers to Events

Also in an event receiver class, you use the intrinsic function \_\_hook to associate events with event handlers and \_\_unhook to dissociate events from event handlers. You can hook several events to an event handler, or several event handlers to an event.


##### Firing Events

To fire an event, simply call the method declared as an event in the event source class. If handlers have been hooked to the event, the handlers will be called.
 
  ____________________________________________________________________________________________________________________________________________


### Singleton:
 In order to use a singleton in C++, make sure it is tread safe and never null. make sure it is created only once.
 
 Depending on your system requirements, yes you can use  "lazy" implementation.
 
  ____________________________________________________________________________________________________________________________________________


### Procedural Programming:
 * C++ has procedural coding that is done inside of objects.  Because of this, C++ does support procedural programing.
 
  ____________________________________________________________________________________________________________________________________________


### Functional Programming:
 * C++ implements functional programming.  It uses functions in order to implement code.
 
  ____________________________________________________________________________________________________________________________________________


### Multithread:
 Multithreading is the ability to run mutlitple threads of execution, or the smallest sequences of coding. Essentially this just means that programs run several threads at the sime time on different processors or cores. This is possible with C++, where there are just program multiple threads in the fnction, and they will all run at the same time.
