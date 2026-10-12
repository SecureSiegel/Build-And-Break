# Lesson 04 - Classes and Encapsulation

## Our goal

I will teach you how a class groups related data and operations, and how private members help protect an object's state.

## What I will teach

A class describes a type of object. Its public section is the interface other code can use; its private section holds implementation details that callers should not change directly. A constructor gives a new object a valid starting state. A `const` member function promises not to change the object.

We will describe the class from the perspective of the problem. A fraction needs a numerator and denominator and operations that make sense for fractions. The class should help prevent invalid states such as a zero denominator.

## Guided steps

1. List the data a fraction needs: numerator and denominator.
2. Decide which operations belong to the class: read or construct, add, subtract, multiply, divide, and display.
3. Declare the class with private data and public operations.
4. Add constructors for a default fraction, an integer fraction, and a numerator/denominator pair.
5. Implement multiplication and addition, then test with fractions whose answers you can calculate by hand.
6. Discuss how the class should handle a zero denominator and division by a zero fraction.

## Practice

- Add subtraction and division tests.
- Normalize a fraction by dividing numerator and denominator by their greatest common divisor.
- Add a getter for each field without making the fields public.

## Check for understanding

- What belongs in the public interface, and what should remain private?
- Why should a constructor establish valid data?
- Why might a member function be marked `const`?

## Source connection

The `Sept12/Fraction Class Example` includes constructors, private numerator/denominator fields, accessors, and arithmetic methods. Some original operations do not check invalid denominators; we will include those cases in our design and tests.
