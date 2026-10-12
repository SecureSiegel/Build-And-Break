# Lesson 07 - Object Lifetimes and Destructors

## Our goal

I will help you understand when an object is created, how long it remains available, and what a destructor does when its lifetime ends.

## What I will teach

A constructor runs when an object is created. A destructor runs when the object is destroyed. Local objects usually end their lifetime when execution leaves the scope where they were created. Resource-owning objects may need cleanup, but modern C++ library types often manage their own resources.

We will distinguish an object's ordinary data from resources it owns. If a class owns a file handle or dynamically allocated memory, its design must ensure cleanup occurs exactly once. For new designs, we will prefer standard library types and RAII rather than hand-written ownership when possible.

## Guided steps

1. Write a small class that prints a message from its constructor and destructor.
2. Create an object inside a nested scope and observe when each message appears.
3. Create multiple objects and predict the order in which they are destroyed.
4. Discuss what the class would need to do if it owned a file or allocated memory.
5. Compare manual cleanup with a standard library type that manages its own resource.

## Practice

- Add a constructor parameter and verify the object begins with the expected value.
- Put two objects in different scopes and sketch their lifetimes.
- Explain why calling `delete` on the same pointer twice is unsafe.

## Check for understanding

- When does a local object's destructor run?
- What kind of responsibility might a destructor have?
- Why does RAII reduce the chance of forgetting cleanup?

## Source connection

The `Sept21/Bookstore` class example and `Oct5/Homework` files introduce constructors and destructors. We will focus on lifecycle concepts and avoid adding manual resource management where standard C++ already provides safer tools.
