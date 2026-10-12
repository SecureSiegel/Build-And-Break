# Lesson 02 - Variables, Input, and Calculations

## Our goal

I will teach you how to store information in variables, ask the user for input, choose useful number types, and calculate a result.

## What I will teach

A variable is a named place to store a value. We will use `int` for whole numbers and `double` for numbers that may have a fractional part. `std::cin` reads input, and arithmetic operators such as `+`, `-`, `*`, and `/` let us calculate with it.

Before coding, we will name the inputs, write down the formula, and check the result with a simple example. A program can run and still calculate the wrong formula.

## Guided steps

1. Write down the problem: ask for the length and width of a rectangle, then show its area.
2. Identify the inputs (`length`, `width`) and the result (`area`).
3. Write the formula on paper: `area = length * width`.
4. Build and run this program:

   ```cpp
   #include <iostream>

   int main() {
       double length = 0.0;
       double width = 0.0;

       std::cout << "Enter the length: ";
       std::cin >> length;
       std::cout << "Enter the width: ";
       std::cin >> width;

       const double area = length * width;
       std::cout << "The area is " << area << '\n';
       return 0;
   }
   ```

5. Test with length `5` and width `3`. Check that the answer is `15`.
6. Change the program to calculate the area of a triangle using `base * height / 2.0`.

## Practice

- Make a two-number addition calculator.
- Calculate a circle's area using `3.14159 * radius * radius`. Test radius `2`; the result should be about `12.56636`.
- For each program, label which variables are inputs and which hold calculated results.

## Check for understanding

- When would I choose `int`, and when would I choose `double`?
- What values do we need to calculate a rectangle's area?
- Why do we test a formula with values whose result we can check ourselves?

## Source connection

The `Jan17` files calculate areas, and `Jan19` adds two numbers. `ASSIGNMENT 1` combines score inputs and calculations. One old circle example multiplies pi by the radius only; our test helps us catch that the radius must be squared.
