# Java_Interview_Prep_Assignment
JAVA Platform : <br>
Problem 1: Why is Java so Popular?  <br>

A: Java is popular for many reasons, including its simplicity, portability, and versatility. Java is an object-oriented language, making it easy to learn and understand. It is also platform-independent, meaning it can run on any platform without modification. Additionally, Java has a large and active community, making it easy to find support and resources.

Problem 2: What is Platform Independence?  <br>

A: Platform independence in Java refers to the ability of Java code to run on any platform without modification. This is achieved by compiling Java code into bytecode, which is then interpreted by the Java Virtual Machine (JVM). The JVM is available on all platforms, allowing Java programs to run on any system with a JVM installed.

Problem 3: What is ByteCode?  <br>

A: Bytecode in Java is the compiled form of Java source code. When a Java program is compiled, the source code is translated into bytecode instructions that can be executed by the Java Virtual Machine (JVM). Bytecode is a platform-independent format, meaning it can be executed on any system that has a JVM installed.

Problem 4: Compare JDK vs JVM VS JRE.  <br>

A: The JDK, JVM, and JRE are three different components of the Java platform. The JDK (Java Development Kit) is a software development kit that includes the tools needed to develop Java applications, including a compiler, debugger, and other development tools. The JVM (Java Virtual Machine) is the component of the Java platform that executes Java bytecode. The JRE (Java Runtime Environment) is a subset of the JDK that includes only the components needed to run Java applications, including the JVM and the Java class library.

Problem 5: What is the role of class loader in Java?  <br>

A: The class loader in Java is responsible for loading Java classes into memory at runtime. The class loader searches for and loads class files from the file system or network, and then verifies and links the classes before they are used by the JVM. There are three types of class loaders in Java: bootstrap class loader, extension class loader, and application class loader. The class loader plays a critical role in Java's ability to dynamically load classes and provide platform independence.



Wrapper Class : <br> 
Problem 1:  What are wrapper classes? <br> 

A: In Java, wrapper classes are used to represent primitive data types (int, char, boolean, etc.) as objects. They provide a way to convert primitive data types into objects and also provide several utility methods to work with these objects.

Problem 2: Why do we need Wrapper Classes in Java? <br> 

A: Wrapper classes are needed in Java because some of the Java APIs require objects instead of primitive data types. For example, the Collections framework can only work with objects, so we need to convert primitive data types to objects using wrapper classes. Additionally, wrapper classes provide useful methods for manipulating and working with these objects.

Problem 3: What are the different ways of creating Wrapper Class Instances?<br> 

A: There are two ways to create Wrapper Class Instances in Java - using the constructor of the wrapper class or using valueOf() method of the wrapper class.

Problem 4: What are differences in the two ways of creating wrapper classes? <br> 

A: The main difference between the two ways of creating wrapper classes is that using the constructor always creates a new object, while using the valueOf() method may reuse an existing object from the cache if the value falls within a certain range.

Problem 5: What is Auto Boxing? <br> 

A: Auto Boxing is a feature introduced in Java 5 that automatically converts primitive data types into their corresponding wrapper classes when necessary. This allows developers to use primitive data types and wrapper classes interchangeably in code.

Problem 6: What is Casting? <br> 

A: Casting is the process of converting a variable of one data type to another data type. In Java, this can be done implicitly or explicitly, depending on the data types involved.

Problem 7: What is Implicit Casting? <br> 

A: Implicit casting, also known as widening conversion, is the automatic conversion of a variable from a lower precision data type to a higher precision data type. For example, when assigning an int value to a double variable, the int value is implicitly cast to a double.

Problem 8: What is Explicit Casting? <br> 

A: Explicit casting, also known as narrowing conversion, is the manual conversion of a variable from a higher precision data type to a lower precision data type. For example, when assigning a double value to an int variable, the double value must be explicitly cast to an int.



Strings : <br>

Problem 1: Are all String’s immutable? <br>

A: Yes, all String objects are immutable in Java. Once a String object is created, its value cannot be changed.

Problem 2: Where are string values stored in memory? <br>

A: String values are stored in a special memory area called the String constant pool, which is a part of the Java heap.

Problem 3: Why should you be careful about String Concatenation(+) operator in Loops? <br>

A: When using the + operator to concatenate Strings in a loop, a new String object is created on each iteration, which can result in a lot of unnecessary memory allocation and impact the performance of the program.

Problem 4: How do you solve above problem? <br>

A: To solve the above problem, we can use the StringBuilder or StringBuffer class to concatenate Strings in a loop as they are mutable and do not create new String objects on each iteration.

Problem 5: What are differences between String and StringBuffer? <br>

A: The main difference between String and StringBuffer is that String is immutable, while StringBuffer is mutable. This means that once a String object is created, its value cannot be changed, whereas a StringBuffer object can be modified.

Problem 6: What are differences between StringBuilder and StringBuffer? <br>

A: The main difference between StringBuilder and StringBuffer is that StringBuilder is not thread-safe, while StringBuffer is thread-safe. This means that StringBuffer is synchronized and can be accessed by multiple threads without any issues, whereas StringBuilder is not synchronized and should not be used in a multi-threaded environment.

Problem 7: Can you give examples of different utility methods in String class? <br> 

A: Yes, some examples of utility methods in String class are:

. length() - returns the length of the String <br>
. charAt(int index) - returns the character at the specified index <br>
. substring(int beginIndex, int endIndex) - returns a substring of the String <br>
. trim() - removes leading and trailing white space <br>
. toUpperCase() - converts the String to uppercase <br>
. toLowerCase() - converts the String to lowercase <br>
. equals(Object obj) - compares the String to the specified object <br>
. indexOf(int ch) - returns the index of the first occurrence of the specified character. <br>

OOPS : <br>
Problem 1: What is a Class? <br>

A: In Java, a class is a blueprint or a template for creating objects. It defines the properties and methods that objects of the class will have.

Problem 2: What is state of an Object? <br>

A: The state of an object refers to the values of its properties or attributes at a given point in time. It represents the current condition or configuration of the object.

Problem 3: What is behavior of an Object? <br>

A: The behavior of an object refers to the actions or operations that can be performed on it. It is determined by the methods or functions defined in the class.

Problem 4: What is the super class of every class in Java? <br>

A: The Object class is the superclass of every class in Java. All classes inherit directly or indirectly from the Object class.

Problem 5: Explain about toString method? <br>

A: The toString method is a method defined in the Object class that returns a string representation of the object. It is often overridden in derived classes to provide a customized string representation.

Problem 6: What is the use of equals method in Java? <br>

A: The equals method in Java is used to compare two objects for equality. It is used to determine whether two objects have the same value or not.

Problem 7: What are the important things to consider when implementing equals method? <br>

A: The important things to consider when implementing equals method are:
. The method should be reflexive: a.equals(a) should return true. <br>
. The method should be symmetric: a.equals(b) should return true if and only if b.equals(a) returns true. <br>
. The method should be transitive: if a.equals(b) and b.equals(c) return true, then a.equals(c) should also return true. <br>
. The method should be consistent: a.equals(b) should return the same value each time it is called. <br>
. The method should return false if the argument is null. <br>

Problem 8: What is the hashCode method used for in Java? <br> 

A: The hashCode method in Java is used to generate a hash code value for an object. The hash code is used by data structures such as hash tables and hash maps to store and retrieve objects efficiently.

Problem 9: Explain inheritance with Examples. <br> 

A: Inheritance is a mechanism in Java by which a class can inherit the properties and methods of another class. The class that inherits is called the subclass or derived class, and the class that is inherited from is called the superclass or base class. For example, consider a class hierarchy consisting of a superclass "Animal" and two subclasses "Cat" and "Dog". Both "Cat" and "Dog" inherit the properties and methods of "Animal" such as "name" and "move()".

Problem 10: What is Method Overloading? <br> 

A: Method Overloading is a feature in Java that allows a class to have multiple methods with the same name but different parameters. It is used to provide different ways of calling a method with different input parameters.

Problem 11: What is Method Overriding? <br>

A: Method Overriding is a feature in Java that allows a subclass to provide its own implementation of a method that is already defined in the superclass. It is used to provide a specialized implementation of a method in the subclass.

Problem 12 : Can super class reference variable hold an object of sub class? <br>

A: Yes, a super class reference variable can hold an object of a subclass. This is known as upcasting.
