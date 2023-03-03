# Object-Oriented Programming Pillars

## Learning Goals

- Define Object-Oriented Programming.
- Introduce the 4 pillars of Object-Oriented Programming.

## Introduction to Object-Oriented Programming

**Object-Oriented Programming** or OOP for short is a model that is dependent
upon the use of classes, objects, methods, and attributes. It's a programming
paradigm that focuses on concepts rather than the logic, like objects, to
perform tasks and implement real-world entities.

## 4 Pillars of Object-Oriented Programming

Java is just one of the many OOP languages out there. Some other OOP languages
are Javascript, TypeScript, Ruby, and Python. These languages all take on a
different syntax from each other, but one thing we can count on is that each
object-oriented programming language has these four pillars in common:

- Encapsulation
- Inheritance
- Polymorphism
- Abstraction

Each of these pillars will be its own lesson where we will delve more into
detail about the pillar and how it is applied in Java. For now, let us define
each of these, so we are familiar with the term once we reach that lesson.

We'll delve into detail about each pillar in the coming lessons. For now, let us
define each of these, so we are familiar with the terms.

### Encapsulation

**Encapsulation** is a programming mechanism that wraps up data in a single
unit and keeps it safe from outside interference. This means that each object in
Java should be in charge of its own state. We can think about our classes and
the instance variables that were encapsulated inside them - usually with the
`private` access modifier. This concept pairs nicely with another concept called
**data hiding**, which is when we can restrict the access on a specific piece of
data.

### Inheritance

**Inheritance** is a mechanism in which one class is allowed to inherit the
features (attributes and methods) of another class. The class that allows
another class to inherit its features is usually referred to as the **base**
**class** or **parent class** whereas the class that is inheriting its features
is called the **derived class** or the **child class**. Inheritance can be
thought of as hierarchical classification. This is an important pillar as it
allows an object to only define common features once and will reduce the amount
of duplicate code.

### Polymorphism

**Polymorphism** means "many forms". It is the ability to take on these many
forms and is usually achieved through inheritance and interfaces in Java.
Polymorphism helps reduce complexity by having objects share certain behaviors
and allowing the overriding of methods. Let's think about a steering wheel in a
car. The steering wheel is the same despite the type of steering mechanism used
beneath the hood. It doesn't matter if the car has manual steering or power
steering, we know how to use a steering wheel even if it takes on different
characteristics. That is how polymorphism works.

### Abstraction

When we abstract something, we want to hide the implementation details. We don't
need to necessarily understand the details of every single method or every
single object in order to use it. That is the idea of **abstraction** - knowing
how to use it or what it is without knowing exactly how it was developed. To
give a more concrete example, think of a car. We know how to accelerate a car
and that is by pressing on the gas pedal. We also know how to decelerate a car
or bring it to a stop, and that is by applying the brakes. We don't need to be
mechanics to know exactly how to use or operate the car, but we know how to use
a car enough to drive it around and what the brakes and gas pedal are supposed
to do. The inner mechanisms are abstracted to the driver. We aren't expected as
developers to understand every single detail about every class. For example, we
have been using the `Scanner` class and `Random` class without knowing exactly
how they were implemented. This is because it is abstracted. We only need to
concern ourselves with how to use the methods of interest, like `nextInt()`.

Abstraction is the core pillar to the object-oriented programming. Without it,
the other pillars wouldn't be able to stand on their own.

![oop-pillars](https://curriculum-content.s3.amazonaws.com/java-mod-3/oop-pillars/principles-of-oo.png)

[4 Principles of Object-Oriented Programming](https://khalilstemmler.com/articles/object-oriented/programming/4-principles/)

## Conclusion

Object-Oriented Programming consists of 4 pillars:

- Encapsulation
- Inheritance
- Polymorphism
- Abstraction

Let us explore each of these pillars and fundamentals some more in the coming
lessons.

## References

- [4 Principles of Object-Oriented Programming](https://khalilstemmler.com/articles/object-oriented/programming/4-principles/)
- [Java: A beginner's Guide, Ninth Edition](https://learning.oreilly.com/library/view/java-a-beginners/9781260463569/ch1.xhtml#lev1_25)
