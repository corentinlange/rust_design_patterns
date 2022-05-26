# Rust design patterns

## **BIG PICTURE OF POO**

### **Four Pillars**
___
- **Abstraction**: model of a real-world object or phenomenon,
limited to a specific context, which represents all details relevant to this context with high accuracy and omits all the rest.

- **Encapsulation**: ability of an object to hide parts of its
state and behaviors from other objects, exposing only a limited interface to the rest of the program.

- **Inheritance**: ability to build new classes on top of existing ones. The main benefit of inheritance is code reuse.

- **Polymorphism**: ability of a program to detect the real
class of an object and call its implementation even when its
real type is unknown in the current context



### **Relations between objects**
___
- **Dependency**: Class А can be affected by changes in class B

- **Association**: Object А knows about object B. Class A depends
on B.

- **Aggregation**: Object А knows about object B, and consists of B.
Class A depends on B.

- **Composition**: Object А knows about object B, consists of B, and
manages B’s life cycle. Class A depends on B.

- **Implementation**: Class А defines methods declared in interface
B. Objects A can be treated as B. Class A depends on B.

- **Inheritance**: Class А inherits interface and implementation of
class B but can extend it. Objects A can be treated as B. Class
A depends on B.

### **Keywords**
___
- **Interface**: Public part of an object, open to interactions with other objects.

