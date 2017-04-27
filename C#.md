# C#
Back To
[Home Page](https://github.com/nasz8f/4330-7330_Final_Project/blob/master/README.md)


### Language Purpose:
 *  When Microsoft developed .Net they developed Pool alogn with it.  By the time .Net was publibly announced in July 2000, it was announced that Pool was renamed to C# for legal reasons. The creator of C# stated that flaws in most OO languages (one of which being C++) drove CLR which drove the design of C#.
 
 
 * While people believed that a new programming language was not needed, C# was developed, derived from C and C++.  It was created to fix problems in C/C++ such as memory leaks, difficulty writing multithreaded applications, static linking, overly complex multiple inheritence rules...etc, making these functions of these languages easier to use.  The end product ended up being very similar to java.

_____________________________________________________________________________________________________________________________________________

### Features:
* Pointers are missing in C#.
* Unsafe operations such as direct memory manipulation are not allowed.
* In C# there is  no usage of "::" or "->" operators.
* Since it's on .NET, it inherits the features of automatic memory management and garbage collection.
* Varying ranges of the primitive types like Integer,Floats etc.
* Integer values  of 0 and 1 are no longer accepted as boolean values.Boolean values are pure true or false values in C# so no more errors of "="operator and "=="operator.
* "==" is used for comparison operation and "=" is used for assignment operation.
* C# supports Data Encapsulation, inheritance,polymorphism, interfaces.
* (int,float, double) are not objects in java but C# has introduces structures(structs) which enable the primitive types to become objects.

_____________________________________________________________________________________________________________________________________________

### Name Spaces:
 * There are two ways namespaces are implemented in C#, one way is using the .NET framework to organize classes.  For example, 'System' is a namespace and 'Console' is a class in said namespace.  To implement this you would type 'System.Console' followed by a command.  If at the top of the program you write 'using [namespace]' for example, 'using System', the name of the namespace would not have to be written before the name of the class each time. The second way of implementing namespaces  is to declare a namespace at the beginning of a program using the keyword 'namespace' followed by a custom name for the namespace.  This allows you to create your own namespace instead of using a default one.  Implementing namespaces allows you to organize large projects.
 
 * The keyword namespace declares a scope that contains a set of objects.  Namespaces can be used to create globally unique types as well as organize elements in your code. A namespace may declare things such as an interface, class, enum, struct, and delegate, as well as another namespace.  If a namespace is not added to a project, the compiler will add a default namespace named 'root'.

_____________________________________________________________________________________________________________________________________________

### Types:
* #### Short Name : type

  byte : Unsigned integer

  sbyte : Signed integer

  int : Signed integer 

  uint : Unsigned integer 

  short : Signed integer 

  ushort : Unsigned integer 

  long : Signed integer 

  ulong : Unsigned integer

  float : Single-precision floating point type

  double : Double-precision  floating point type 

  char : A single Unicode  character 

  bool : Logical Boolean type

  object : Base type of all other types 

  string : A sequence of characters 

  decimal : Precise fractional or integral type that can represent decimal numbers with 29 significant digits 


 * C# supports both value and reference types. When a variable is declared using one of the basic, built-in data types or a user defined structure, it is a value type. An exception is the string data type, which is a reference type. A value type stores its contents in memory allocated on the stack. In contrast, a reference type, such as an instance of a class or an array, is allocated in a different area of memory called the heap. 

* New value types can be created in C#. With user-defined types, you can use new to invoke the default constructor. 

_____________________________________________________________________________________________________________________________________________

### Classes:
* A class can be defined choosing an access level such as publuc, private, protected, or default.  This is followed by the keyword 'class' and then the custom name of your class.

* A new object, or instance, can be created in a class by using the 'new' keyword, followed by the name of the class that the instance is based on.

* When initializing a class, its constructor is called.  To create a class's constructor an access level must be chosen, followed by the keyword 'class' since the constructor shares the same name as the class and it's custom name.  This is to be created somewhere above the class that uses it.  The class can then be instantiated using the constructor by using the keyword 'new'.

* In C# a class may only have one deconstructor which can't be called.  A deconstructor is invoked automatically.  It doesn't hve modifiers or parameters. A deconstructor may be created by calling the keyword 'class' with the class's custom name. Inside of the brackets of this, the name of the class preceded by a '~' and followed by '()'.  This will deconstruct a class.
 
 ____________________________________________________________________________________________________________________________________________

### Instance Reference in Data Type:
* C# uses the this parameter to refer to the current instance of a class.  The 'this' keyword can also be used as a modifier for an extension method.

* In C#, getter and setters must be written using the 'get' and set' accessors.  The get accessor is executed when a property is read while the set accessor is executed when a property is assigned a new value.

* C# supports backing variables.  A backing variable is a private field that stores the data exposed by a public property.  In C# a backing variable is referred to as a backing store or backing field.

* A calculated property can be a replacement for a method in C# as long as they don't take a noticable amount of time.  It is when one property is computed by another.
 
 ____________________________________________________________________________________________________________________________________________

### Properties:
* In C#, getter and setters must be written using the 'get' and set' accessors.  The get accessor is executed when a property is read while the set accessor is executed when a property is assigned a new value.

* C# supports backing variables.  A backing variable is a private field that stores the data exposed by a public property.  In C# a backing variable is referred to as a backing store or backing field.

* A calculated property can be a replacement for a method in C# as long as they don't take a noticable amount of time.  It is when one property is computed by another.
 
  ____________________________________________________________________________________________________________________________________________


### Interfaces/Protooals:
 * C# supports interfaces.  The 'interface' keyword includes behavior from multiple sources in a class.  This is important since C# does not support multiple inheritance in a class.

* An interface can inherit from other interfaces.  It allows a 'simulation' inheritance for structs.  It is like a simulation because it can not actually inherit from another struct or class.

* For an inteface to be used, it must be initialized by using the keyword 'interface' followed by a custom name.  This can be called in a class by writing the name of the intercafe after the class name separated by a ':'.  When a class uses an interface, it must provide an implementation for every member that the interface defines.
 
  ____________________________________________________________________________________________________________________________________________


### Inheritance/Extension:
* C# supports inheritance, however it does not support multiple inheritance.  Multiple inheritance however, can be simulated using an interface.  C# also does not support extension.
 
  ____________________________________________________________________________________________________________________________________________


### Reflection:
 * Reflection in C# can dynamically create an instance of a type, bind the type to an existing object, and get the type from an existing object and invoke it's methods to access fields and properties.
 
 * Reflection is useful in the following situations:
 When you have to access attributes in your program's metadata.
 For examining and instantiating types in an assembly.
 For building new types at runtime.
 For performing late binding, accessing methods on types created at run time
 
  ____________________________________________________________________________________________________________________________________________


### Memory Management:
 * C# Supports automatic memory management so that developers do not have to worry about allocating and freeing memory.  This is implemented by a garbage collector.  Once an object is finished being used it is ready for deconstroction.  Sometime later the deconstructor is run once.  After the deconstructor is run, the object is inaccessable.  The object then becomes eligible for collection and the garbage collector collects it.
 
  ____________________________________________________________________________________________________________________________________________


### Comparisons of Reference and Values:
 * In C# two non string values can be compared with an '==' '<=' '!=' or '>='.  To compare strings however, the funtion String.equals(firstString, secondString, StringComparison.Ordinal).
 
  ____________________________________________________________________________________________________________________________________________


### Null References:
 * C# used null.
 
 * The 'null' keyword represents a null reference. While ordinary value types are not allowed to be null, C# has nullable value types.
 
  ____________________________________________________________________________________________________________________________________________


### Errors and Exception Handling:
* C# uses the 'try' keyword to partition code that could be affected by an exception.  A 'try' block needs either a 'catch; block or 'finally' block or both to work.  The 'catch' keyword is used to handle an exception that comes from this.  The 'finally' keyword has code that runs no matter if an exception is thrown or not with the 'try' keyword.
 
  ____________________________________________________________________________________________________________________________________________


### Lambda Expressions/Closures/Functions as Types:
 * In C# a lambda expression lets one create delegates or expression tree types.  Lambda expressions allow for local functions to be passed as arguments or returned as the value from said function.  A lambda expression can be created in C# by specifying parameters on the left side of the expression, followed by a statement block, preceded by a '=>'.
 
  ____________________________________________________________________________________________________________________________________________


### Implementation of Listeners and Event Handlers:
* In C#, events are based on a delegate model which enables a subscriber to register with and receive notifications from.  An event sender pushes a notification and event.  An event receiver then receives the notification and responds.
 
  ____________________________________________________________________________________________________________________________________________


### Singleton:
 * In C# a singleton is typically specified without parameters.  There are multiple ways of implementing a singleton in C#.  All implimentations share four characteristics.  Each implementation contains one constructor (private and parameterless), The class is sealed, there is a static variable which holds reference to an instance, and there is a public static way of getting reference to said instance.
 
 * In C# a singleton can be either thread-safe or non thread-safe.
 
 * Singletons must be created lazily in C#
 
  ____________________________________________________________________________________________________________________________________________


### Procedural Programming:
 * The functionality of C# is logically procedural.
 
  ____________________________________________________________________________________________________________________________________________


### Functional Programming:
 * C# has all the features needed for functional programming.  These consist of higher order functions, closures, and lanbda expressions
 
  ____________________________________________________________________________________________________________________________________________


### Multithread:
 * In C# a thread can be created by using the 'Thread' keyword and calling the constructor for the method one would want to execute the thread on.  A thread can be started with the keyword 'Start' and ended witht the keyword 'Abort'.  These threads allow multiple tasks to be run at the same time.  Tasks that have potential to hold up other tasks can be executed on seperate threads.
 
 * Multitasking is accomplished by writing processor-intensive tasks on seperate threads.  More threads should be added as the workload of a project increases.
