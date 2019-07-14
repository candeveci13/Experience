Lazy loading is a design pattern commonly used in computer programming to defer initialization of an object until the point at which it is needed.
It can contribute to efficiency in the program's operation if properly and appropriately used.
The opposite of lazy loading is eager loading.
The performance gains are especially significant if the initialization of the object is costly, such as in case of accessing network services.
This makes it ideal in use cases where network content is accessed and initialization times are to be kept at a minimum, such as in the case of web pages.


The Golden Rule of Programming
For years I have had a saying that I say to my team all the time. I call it the golden rule of programming.  I think every new programmer needs a tattoo that says it.
“If it can be null, it will be null” The good news is that a lot of null reference errors can be avoided by adding additional logic and code to ensure objects are not 
null before trying to use them. Developers should always assume that everything is invalid and be very defensive in their code. 
Pretend every database call is going to fail, every field is going to have messed up data in it. Good exception handling best practices are critical.

http://gitmostwanted.com/

Clean Code Principles
https://github.com/labs42io/clean-code-typescript


Singleton
http://csharpindepth.com/Articles/General/Singleton.aspx

Factory
https://www.c-sharpcorner.com/article/factory-method-design-pattern-in-c-sharp/

Strategy
https://www.dofactory.com/net/strategy-design-pattern
https://www.gokhan-gokalp.com/c-strategy-pattern-kullanimi/

Observer
https://www.dofactory.com/net/observer-design-pattern
https://www.gokhan-gokalp.com/c-observer-pattern-kullanimi/

Builder
https://www.dofactory.com/net/builder-design-pattern

Adapter
https://www.dofactory.com/net/adapter-design-pattern
https://www.geeksforgeeks.org/adapter-pattern/

State
https://www.dofactory.com/net/state-design-pattern
https://en.wikipedi0.org/wiki/State_pattern


Most Used Patterns
https://medium.com/educative/the-7-most-important-software-design-patterns-d60e546afb0e



Most Used patterns
1-Singleton
2-Factory
3-Strategy
4-Observer
5-Builder
6-Adapter
7-State



Creational patterns are ones that create objects for you, rather than having you instantiate objects directly. This gives your program more flexibility in deciding which objects need to be created for a given case.

    -Abstract factory pattern groups object factories that have a common theme.
    +Builder pattern constructs complex objects by separating construction and representation.
    +Factory method pattern creates objects without specifying the exact class to create.
    -Prototype pattern creates objects by cloning an existing object.
    +Singleton pattern restricts object creation for a class to only one instance.

Structural

These concern class and object composition. They use inheritance to compose interfaces and define ways to compose objects to obtain new functionality.

    +Adapter allows classes with incompatible interfaces to work together by wrapping its own interface around that of an already existing class.
    -Bridge decouples an abstraction from its implementation so that the two can vary independently.
    -Composite composes zero-or-more similar objects so that they can be manipulated as one object.
    -Decorator dynamically adds/overrides behaviour in an existing method of an object.
    -Facade provides a simplified interface to a large body of code.
    -Flyweight reduces the cost of creating and manipulating a large number of similar objects.
    -Proxy provides a placeholder for another object to control access, reduce cost, and reduce complexity.

Behavioral

Most of these design patterns are specifically concerned with communication between objects.

    -Chain of responsibility delegates commands to a chain of processing objects.
    -Command creates objects which encapsulate actions and parameters.
    -Interpreter implements a specialized language.
    -Iterator accesses the elements of an object sequentially without exposing its underlying representation.
    -Mediator allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
    -Memento provides the ability to restore an object to its previous state (undo).
    +Observer is a publish/subscribe pattern which allows a number of observer objects to see an event.
    +State allows an object to alter its behavior when its internal state changes.
    +Strategy allows one of a family of algorithms to be selected on-the-fly at runtime.
    -Template method defines the skeleton of an algorithm as an abstract class, allowing its subclasses to provide concrete behavior.
    -Visitor separates an algorithm from an object structure by moving the hierarchy of methods into one object.


All Algorithms implemented in Python
    https://github.com/TheAlgorithms/Python
    
    
spaCy is not a platform or “an API”. Unlike a platform, spaCy does not provide a software as a service, or a web application. 
It’s an open-source library designed to help you build NLP applications, not a consumable service.