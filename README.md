# Java_Interview_Prep_Assignment
JAVA Platform : 
Problem 1: Why is Java so Popular?

Q: Why is Java such a popular programming language?
A: Java is popular for many reasons, including its simplicity, portability, and versatility. Java is an object-oriented language, making it easy to learn and understand. It is also platform-independent, meaning it can run on any platform without modification. Additionally, Java has a large and active community, making it easy to find support and resources.

Problem 2: What is Platform Independence?

Q: What is platform independence in Java?
A: Platform independence in Java refers to the ability of Java code to run on any platform without modification. This is achieved by compiling Java code into bytecode, which is then interpreted by the Java Virtual Machine (JVM). The JVM is available on all platforms, allowing Java programs to run on any system with a JVM installed.

Problem 3: What is ByteCode?

Q: What is bytecode in Java?
A: Bytecode in Java is the compiled form of Java source code. When a Java program is compiled, the source code is translated into bytecode instructions that can be executed by the Java Virtual Machine (JVM). Bytecode is a platform-independent format, meaning it can be executed on any system that has a JVM installed.

Problem 4: Compare JDK vs JVM VS JRE.

Q: What is the difference between JDK, JVM, and JRE in Java?
A: The JDK, JVM, and JRE are three different components of the Java platform. The JDK (Java Development Kit) is a software development kit that includes the tools needed to develop Java applications, including a compiler, debugger, and other development tools. The JVM (Java Virtual Machine) is the component of the Java platform that executes Java bytecode. The JRE (Java Runtime Environment) is a subset of the JDK that includes only the components needed to run Java applications, including the JVM and the Java class library.

Problem 5: What is the role of class loader in Java?

Q: What is the role of the class loader in Java?
A: The class loader in Java is responsible for loading Java classes into memory at runtime. The class loader searches for and loads class files from the file system or network, and then verifies and links the classes before they are used by the JVM. There are three types of class loaders in Java: bootstrap class loader, extension class loader, and application class loader. The class loader plays a critical role in Java's ability to dynamically load classes and provide platform independence.



Wrapper Class : 
Problem 1:
Question: What are wrapper classes?
Answer: In Java, wrapper classes are used to represent primitive data types (int, char, boolean, etc.) as objects. They provide a way to convert primitive data types into objects and also provide several utility methods to work with these objects.

Problem 2:
Question: Why do we need Wrapper Classes in Java?
Answer: Wrapper classes are needed in Java because some of the Java APIs require objects instead of primitive data types. For example, the Collections framework can only work with objects, so we need to convert primitive data types to objects using wrapper classes. Additionally, wrapper classes provide useful methods for manipulating and working with these objects.

Problem 3:
Question: What are the different ways of creating Wrapper Class Instances?
Answer: There are two ways to create Wrapper Class Instances in Java - using the constructor of the wrapper class or using valueOf() method of the wrapper class.

Problem 4:
Question: What are differences in the two ways of creating wrapper classes?
Answer: The main difference between the two ways of creating wrapper classes is that using the constructor always creates a new object, while using the valueOf() method may reuse an existing object from the cache if the value falls within a certain range.

Problem 5:
Question: What is Auto Boxing?
Answer: Auto Boxing is a feature introduced in Java 5 that automatically converts primitive data types into their corresponding wrapper classes when necessary. This allows developers to use primitive data types and wrapper classes interchangeably in code.

Problem 6:
Question: What is Casting?
Answer: Casting is the process of converting a variable of one data type to another data type. In Java, this can be done implicitly or explicitly, depending on the data types involved.

Problem 7:
Question: What is Implicit Casting?
Answer: Implicit casting, also known as widening conversion, is the automatic conversion of a variable from a lower precision data type to a higher precision data type. For example, when assigning an int value to a double variable, the int value is implicitly cast to a double.

Problem 8:
Question: What is Explicit Casting?
Answer: Explicit casting, also known as narrowing conversion, is the manual conversion of a variable from a higher precision data type to a lower precision data type. For example, when assigning a double value to an int variable, the double value must be explicitly cast to an int.
