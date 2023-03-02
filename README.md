# Object-Oriented Programming Pillars

## Learning Goals

- Review the definition of Object-Oriented Programming
- Define the 4 pillars of Object-Oriented Programming

## Review Object-Oriented Programming

In the last module, we defined Object-Oriented Programming (OOP). But let's
review that definition again: OOP is a model that is dependent upon the use of
classes, objects, methods, and attributes. It's a programming paradigm that
focuses on concepts rather than the logic, like objects, to perform tasks and
implement real-world entities.

## 4 Pillars of Object-Oriented Programming

Java is just one of the many OOP languages out there. Some other OOP languages
are Javascript, TypeScript, Ruby, and Python. These languages all take on a
different syntax from each other, but one thing we can count on is that each
object-oriented programming language has these four pillars in common:

- Encapsulation
- Inheritance
- Abstraction
- Polymorphism

Each of these pillars will be its own lesson where we will delve more into
detail about the pillar and how it is applied in Java. For now, let us define
each of these, so we are familiar with the term once we reach that lesson.

### Encapsulation

**Encapsulation** is a programming mechanism that wraps up data in a single
unit and keeps it safe from outside interference. This means that each object in
Java should be in charge of its own state. We can think about our classes and
the instance variables that were encapsulated inside them - usually with the
`private` access modifier. We can think of this as "data-hiding" and can use the
term "encapsulation" and "data-hiding" synonymously.

### Inheritance

**Inheritance** is a mechanism in which one class is allowed to inherit the
features (attributes and methods) of another class. The class that allows
another class to inherit its features is usually referred to as the **base**
**class** or **parent class** whereas the class that is inheriting its features
is called the **derived class** or the **child class**. Inheritance can be
thought of as hierarchical classification. This is an important pillar as it
allows an object to only define common features once and will reduce the amount
of duplicate code.

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
to do. The inner mechanisms are abstracted to the driver.

### Polymorphism

**Polymorphism** means "many forms". It is the ability to take on these many
forms and is usually achieved through inheritance and interfaces in Java.
Polymorphism helps reduce complexity by objects sharing certain behaviors and
allowing overriding of methods. Let's go back to the car example and think about
a steering wheel. The steering wheel is the same despite the type of steering
mechanism used beneath the hood. It doesn't matter if the car has manual
steering or power steering, we know how to use a steering wheel even if it
takes on different characteristics. That is how polymorphism works.
