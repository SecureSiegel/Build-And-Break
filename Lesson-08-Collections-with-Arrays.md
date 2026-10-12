# Lesson 08 - Collections with Arrays

## Our goal

I will teach you how to store several related values in an array and process them with loops.

## What I will teach

An array stores multiple values of the same type. Each position has an index, and in C++ the first index is `0`. A two-dimensional array uses a row and a column, which works well for a table such as several students' scores.

We must know how many items an array can hold and keep every index within its valid range. We will track the number of records actually read separately from the array's capacity.

## Guided steps

1. Create an array for six test scores and give it a clear capacity.
2. Use a `for` loop to read the scores into indexes 0 through 5.
3. Use a second loop to calculate their total and average.
4. Draw the array as six labeled boxes and match each index to its value.
5. Extend the idea to rows of student records and columns of scores.
6. Test with the first and last valid indexes. Explain what would happen if an index were one too large.

## Practice

- Find the largest of six scores.
- Store scores for three learners in a two-dimensional array and print them as a table.
- Read a list of movie titles from a file and display each title using `std::getline`. Decide how your program will respond if the list exceeds the array capacity.

## Check for understanding

- What is the index of the first array element?
- What is the difference between capacity and the number of items currently stored?
- Which loop variables correspond to rows and columns in a two-dimensional array?

## Source connection

`Mar23` introduces one-dimensional arrays for movie titles. `Mar28` and `Apr4` use rows and columns for names and scores. Those programs give us a natural place to practice indexing, bounds, and nested loops.
