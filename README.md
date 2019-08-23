# Introduction to Object Inheritance in Ruby

The concept of inheritance in Ruby works similarly to the real world--A prince
can inherit a kingdom and everything within it, a baby can inherit genetic
traits from a parent. In Ruby, a class can inherit the behaviors of another
class, referred to as the _superclass_.

In these lessons, we'll cover:
* What inheritance is in object oriented Ruby
* Implementing class with inherited methods from another class that also has its
  own unique methods
* Refactoring "code smells" into multiple, non-repetitive methods
* Using the `super` keyword to inherit from and augment methods in the parent class

In this section, we'll explain how we can leverage the power to define basic
classes with large reusability and smaller subclasses for more fine-grained,
detailed behaviors.