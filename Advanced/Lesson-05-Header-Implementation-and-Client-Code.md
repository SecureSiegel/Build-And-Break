# Lesson 05 - Header Files, Implementation, and Client Code

## Our goal

I will show you how to organize a class into a header and implementation file, then write a separate client program that uses it.

## What I will teach

A header file describes the class interface so other source files can use it. The implementation file defines the class functions. A client file creates objects and calls those functions. Include guards prevent the same header from being processed repeatedly in one build.

This organization separates what a class promises from how it fulfills that promise. We will keep function declarations and definitions consistent and include only the headers we need.

## Guided steps

1. Create `Fraction.h` with an include guard, the class declaration, and necessary standard-library includes.
2. Create `Fraction.cpp` and include `Fraction.h`.
3. Define each member function using the `Fraction::` scope name.
4. Create a client source file that includes `Fraction.h`, creates two fractions, and prints results.
5. Compile and link all source files together.
6. Change one implementation detail without changing the client interface. Confirm the client still works.

## Practice

- Split a simple `Book` or `Product` class into header and implementation files.
- Intentionally misspell a function definition's name and use the compiler/linker error to find the mismatch.
- Explain the roles of a header, implementation file, and client file.

## Check for understanding

- What belongs in the header, and what belongs in the implementation?
- Why does a member definition use `ClassName::functionName`?
- What kind of problem do include guards prevent?

## Source connection

The `Sept12` Fraction example and `Sept14` Goldfish example use a specification/header file, implementation file, and client code. The `Prog1/Turn In/Inventory` project follows the same structure across its inventory files.
