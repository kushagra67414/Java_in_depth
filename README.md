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
