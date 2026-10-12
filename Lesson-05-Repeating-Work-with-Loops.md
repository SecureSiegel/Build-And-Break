# Lesson 05 - Repeating Work with Loops

## Our goal

I will teach you how to repeat instructions with `while` and `for` loops, and how to stop a loop safely.

## What I will teach

A loop is useful when we need to repeat work. A counter-controlled loop repeats a known number of times. A sentinel-controlled loop continues until the user enters a special value, such as `-1`. Every loop needs a clear way to make progress toward stopping.

We will learn to identify the counter, condition, and update. If one of these is missing or incorrect, the loop may repeat forever or stop too soon.

## Guided steps

1. Start with a counter set to zero.
2. Use a `while` loop to print the numbers 1 through 5. Increment the counter during each pass.
3. Draw a small trace table with the counter value and the output for each pass.
4. Write a second program that keeps asking for scores until the user enters `-1`.
5. Test the stopping value first, then test a normal value followed by the stopping value.
6. For a known number of repetitions, rewrite the first loop as a `for` loop.

## Practice

- Ask how many treats are available and count each one being handed out.
- Add a running total to a number-entry loop.
- Use a loop to display the numbers from 1 to 10, skipping 5. Describe exactly what `continue` does if you use it.

## Check for understanding

- What changes each time through a counter-controlled loop?
- What value ends the sentinel loop?
- How can you tell whether a loop might never end?

## Source connection

`Feb14` has counter- and sentinel-controlled examples, and `Feb21` practices nested loops with `break` and `continue`. We will use those control-flow tools carefully and avoid copying examples with an unintended endless outer loop.
