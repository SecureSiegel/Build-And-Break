# Lesson 06 - Reusable Functions

## Our goal

I will help you divide a program into named tasks so each part is easier to understand, test, and reuse.

## What I will teach

A function is a named block of work. It can receive parameters, do a task, and return a result. A function prototype tells C++ about a function before we call it. A `void` function performs a task without returning a value.

We will begin with value parameters. Then we will use a reference parameter (`&`) when a function needs to update a variable that belongs to its caller. We will use that feature intentionally and explain what changes.

## Guided steps

1. Take the rectangle-area program from Lesson 2.
2. Write a prototype above `main`: `double rectangleArea(double length, double width);`
3. Replace the calculation in `main` with a call to `rectangleArea`.
4. Define the function after `main`. Have it return `length * width`.
5. Test the function with more than one pair of values.
6. Add a `void printWelcome()` function and call it near the start of `main`.

## Practice

- Write a function that accepts income and a tax rate and returns the estimated tax.
- Write a function that accepts three scores and returns their average. Use a floating-point calculation so division does not accidentally discard the fractional part.
- Write an input function that fills a first name and last name through reference parameters.

## Check for understanding

- What information does a function prototype give the compiler?
- What is a parameter?
- When is a reference parameter useful?

## Source connection

The `Mar14` and `Mar16` programs introduce calculation functions. `Mar21` demonstrates input through references and a descriptive-header function. `Mar28` breaks a student report into smaller functions.
