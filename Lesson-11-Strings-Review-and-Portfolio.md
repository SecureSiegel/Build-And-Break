# Lesson 11 - Strings, Review, and Portfolio

## Our goal

I will help you review the course, practice text input, and prepare a portfolio that shows what you can do.

## What I will teach

A text record may contain spaces, so reading a line with `std::getline` can be more appropriate than reading a single word with `operator>>`. We will learn to be deliberate when mixing formatted input and whole-line input, because a leftover newline can make `getline` return an empty line.

We will also review how to explain a program: what it is for, what it expects, how it works, what we tested, and what we learned while improving it.

## Guided steps

1. Make a small program that reads and prints a full line of text with `std::getline`.
2. If you first read a number with `std::cin >>`, clear the leftover newline before calling `getline`. Include `<limits>` and use:

   ```cpp
   std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
   ```

   Test the behavior rather than guessing.
3. Choose one earlier program and describe its purpose, input, processing, and output.
4. Run a set of test cases. Keep notes about what passed, what failed, and what you changed.
5. Prepare a portfolio containing selected source files, instructions for running them, sample input/output, and a short reflection in your own words.
6. Present your work. Explain one problem you solved and one improvement you would make next.

## Practice

- Extend the movie-title program to accept titles containing spaces.
- Add clear prompts and error messages to one earlier program.
- Review the course by tracing a value from input, through a calculation or decision, to output.

## Check for understanding

- When is `std::getline` a better choice than `std::cin >> text`?
- What happens if a leftover newline is still waiting in the input stream?
- Can you explain one test that helped you find or prevent a bug?

## Source connection

`FINALS/C.STRINGS` practices character-based text input, and `FINALS/Final Study` contains a final review example. `PORTFOLIO.TXT` and the screenshots folder show the original course's emphasis on collecting and presenting finished work. We will build a portfolio that explains the learning, not just the files.
