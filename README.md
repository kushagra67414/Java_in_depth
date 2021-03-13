# Java_in_depth
Advance Java 

Day-1

* Wine Software is a free and open-source compatibility layer that aims to allow application software and computer games developed for Microsoft Windows to run on Unix-like operating systems.
* Java Virtual MAchine

Day-2

* JVM Architecture
* Mark-Sweep-Compact GC Algorithm
* GC Algorithms: Implementations

[Types of GC ](https://plumbr.io/handbook/garbage-collection-algorithms-implementations)

* young and old generations in GC

```
Young Generation : It is place where lived for short period and divided into two spaces:
•	Eden Space : When object created using new keyword memory allocated on this space.
•	Survivor Space : This is the pool which contains objects which have survived after java garbage collection from Eden space.
Old Generation : This pool basically contains tenured and virtual (reserved) space and will be holding those objects
which survived after garbage collection from Young Generation.
•	Tenured Space: This memory pool contains objects which survived after multiple garbage collection means object 
which survived after garbage collection from Survivor space.
Permanent Generation : This memory pool as name also says contain permanent class metadata and descriptors information
so PermGen space always reserved for classe0s and those that is tied to the classes for example static members.

```
* Java Multithreading
* Dynamic Method Dispatch
* overriding of static and private methods
* constructor chaining 
* method hiding
* static and dynamic binding


## Day-3

* Autoboxing/unboxing
* Wrapper Class
* Reflection in Java

[Reflection in Java](https://www.geeksforgeeks.org/reflection-in-java/)

* Wildcards in JAVA
* Final VS Immutability

[Click Here](https://www.geeksforgeeks.org/final-vs-immutability-java/#:~:text=final%20means%20that%20you%20can,its%20reference%20to%20another%20one.)

* Generics in Java
[Generics](https://www.javatpoint.com/generics-in-java)

* enum in Java
[Enums](https://www.geeksforgeeks.org/enum-in-java/)

* Immutable class -- how to make
[Click Here](https://www.geeksforgeeks.org/create-immutable-class-java/)



## Day-4

* Escaping Reference

[Click Here](https://hashnode.com/post/introduction-to-anatomy-of-escaping-references-using-java-ckdzud9j3000nnas1dbe86d6g)

* Encapsulation in java

[Click Here](https://www.tutorialspoint.com/java/java_encapsulation.htm#:~:text=Encapsulation%20in%20Java%20is%20a,methods%20of%20their%20current%20class.)

* Immutable Class

[Click Here](https://dzone.com/articles/how-to-create-an-immutable-class-in-java)



