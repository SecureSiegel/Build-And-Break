# Lesson 10 - Structs and the Grade-Report Capstone

## Our goal

I will show you how a `struct` can group related information and help us finish a student-grade report capstone.

## What I will teach

A structure lets us define one type that groups related fields. A `Student` can hold a name and a collection of scores together. An array of `Student` values can then represent a class roster. This makes each record easier to reason about than several unrelated arrays with matching indexes.

We will finish the program in small steps and keep each calculation testable. The report should be understandable, correctly formatted, and based on complete records.

## Guided steps

1. Define a `Student` structure with a full name and six scores.
2. Store a small class roster in an array of `Student` values, with a separate count.
3. Write a function that calculates one student's total and averages.
4. Write a function that assigns a grade using the agreed boundaries.
5. Read student records from a file, checking for a successful open and staying within capacity.
6. Print a labeled report to the console and save it to an output file.
7. Test each calculation by hand, then test the whole program with multiple records.
8. Ask a classmate to use the report without your explanation. Improve any labels or instructions that cause confusion.

## Practice

- Add a field for a student ID and include it in the report.
- Add a validation rule for scores and explain how invalid records are handled.
- Extend the program to support a class size that differs from your chosen capacity without writing past the array.

## Check for understanding

- What information belongs together in a `Student`?
- How does a structure make a roster easier to understand?
- What evidence can you show that the report works correctly?

## Source connection

`Program Assignment 5` groups student names, scores, totals, averages, and grades in a structure, then uses functions to process records. The `Apr6` final-study program revisits a file-based report. We will preserve the project ideas while correcting outdated syntax and checking the file and record limits carefully.
