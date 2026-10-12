# Lesson 03 - Text and Clear Output

## Our goal

I will show you how to work with names and other text, combine text with values, and make numeric output easier to read.

## What I will teach

We can store a word or a line of text in a `std::string`. We can join strings with `+` and display labels alongside numbers. A clear report helps another person understand what a program calculated.

For money or averages, we can use `std::fixed` and `std::setprecision`. Those formatting tools affect how values are displayed; they do not change the value stored in a variable.

## Guided steps

1. Create a program that asks for a first name and a bid amount.
2. Include `<string>` for `std::string` and `<iomanip>` for formatting.
3. Read both values and print a labeled result. Use `std::fixed << std::setprecision(2)` for the bid.
4. Try combining the first and last name in a full-name string.
5. Add spaces and labels deliberately. Run the program and check whether another person can read the result without guessing.

## Practice

- Ask for a learner's first and last name and greet them by their full name.
- Ask for three quiz scores and print them with useful labels.
- Print a small two-column report using `std::setw` from `<iomanip>`. Keep the column headings lined up with the values.

## Check for understanding

- What is the difference between a string and a number?
- What does `std::setprecision(2)` do when used with `std::fixed`?
- Why is `"Average: "` more helpful than printing a number with no label?

## Source connection

The `Jan24` program practices auction-bid output and formatting. The `Jan26` quiz examples collect names and scores. We will use `std::string` rather than treating names as numeric variables.
