# Lesson 02 - Arrays, Functions, and References

## Our goal

I will help you use a function to process an array, and show how a reference parameter lets a function update the caller's value.

## What I will teach

An array stores several values of one type, and a loop can process its elements. When an array is passed to a function, the function also needs to know how many elements it may use. An index must stay between zero and one less than the array's size.

A value parameter gives the function a copy. A reference parameter, written with `&`, lets the function work with the caller's original variable. We will choose the form that matches the job.

## Guided steps

1. Create an integer array with a handful of test values.
2. Write a function that receives the array and its size, then returns the sum.
3. Call the function from `main` and compare the result with a hand calculation.
4. Write a second function that orders two integers from smallest to largest using reference parameters.
5. Trace what changes in the caller before and after the function call.
6. Add tests for the smallest supported array and repeated values.

## Practice

- Write a function that finds the largest value in an array.
- Write a function that swaps two values by reference.
- Explain why a function that receives an array should also receive its valid element count.

## Check for understanding

- What is the first valid array index?
- What does a reference parameter allow a function to change?
- Why is an array's capacity not the same thing as a valid index?

## Source connection

The `sept5` array-total example passes an array and element count to a function. The `Sept7` `Order` example modifies two integers by reference. Class notes in `Aug31` compare passing by value with passing by reference.
