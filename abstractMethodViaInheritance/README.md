# inheriting an abstract class

A student asked "Can you have a class declared abstract that has no methods in it marked abstract?"

This directory demonstrates the necessity for that ability.

Inheritance tree:
    Animal
       ^
       |
      Pet
       ^
       |
    Retriever

The Pet class has no methods, but the compiler insists that it be marked abstract.