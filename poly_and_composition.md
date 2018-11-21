**1. What does the word 'polymorphism' mean?**

It means that something is mutable and cheangeable, could have many forms.

**2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.**

Classes that have a superclass inheritance for example due to its common relations or attributes. Inheriting from an abstract class.

**3. What can we use to implement polymorphism in Java?**

Abstract classes and interfaces.

**4. How many 'forms' can an object take when using polymorphism?**

An object can *implement* many interfaces but can only  *inherit* from one another class.

**5. Give an example of when you could use polymorphism.**

When creating multiple classes to which share a same commonality, it is possible to create a super class or interfaces that can organize and divide the responsibility on our program.


**6. What do we mean by 'composition' in reference to object-oriented programming?**

It's a design techinique by which we are able to use instance variables from classes as fields inside other classes.

**7. When would you use composition? Provide a simple example in Java.**

Take the following snipet:
```java
public class CPU extends Player {

    private IStrategy strategy;

    public CPU(IStrategy strategy) {
        this.strategy = strategy;
    }
```

A CPU **is a** chess player, however, a CPU **has a** strategy. In the end, it comes down to design. Whether our class has *components* of another giving class.

**8. What is/are the advantage(s) of using composition?**

Composition comes with important upsides such as flexibility, a new class will have accessibility of the characteristics(i.e. attributes and methods) of a given class. 

Also, better testeability. It is possible to create a mock object with attributes and methods from the old and the newly composed class. 

Amongst other advantages.