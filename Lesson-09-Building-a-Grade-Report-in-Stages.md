# Lesson 09 - Building a Grade Report in Stages

## Our goal

I will guide you through combining functions, decisions, loops, arrays, and file input to create a reliable grade report.

## What I will teach

Large programs become manageable when we build and test one part at a time. We will agree on a record format, read a bounded number of students, validate scores, calculate totals and averages, assign letter grades, and print a report.

We will check assumptions as we go: How many scores are in each record? What is the valid score range? What are the exact grade boundaries? What should happen when input is missing or invalid?

## Guided steps

1. Plan the input format on paper. Use one student per line, with a first name, last name, three program scores, and three test scores.
2. Create and test an input function that reads records. Store a count and never exceed the array capacity.
3. Write and test a score-validation function that accepts values from 0 through 100 and reports invalid values clearly.
4. Write separate functions for total points, program average, test average, course average, and letter grade.
5. Test each calculation with hand-worked scores before connecting it to the full program.
6. Add an output function that prints aligned columns to the screen and to a file.
7. Test an empty file, a valid file, a score at each boundary, a score outside the allowed range, and a file with the maximum supported number of students.

## Practice

- Add a fourth program score and update the input format, total, and program average.
- Change the grade boundaries only after writing them down and agreeing on the rules.
- Add a clear message when there are more input records than the program can store.

## Check for understanding

- Which function reads the records, and which functions calculate results?
- How does the program prevent a score outside 0-100 from being accepted?
- What tests give us confidence that our averages and grade boundaries are correct?

## Source connection

The progression from `Program Assignment 1` through `Program Assignment 4` evolves a grade report from keyboard input to files, functions, and arrays. The `Mar28` and `Apr4` work is our main reference. Some original versions contain calculation and indexing mistakes; we will use small, known test cases to find and correct them.
