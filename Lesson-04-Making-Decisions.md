# Lesson 04 - Making Decisions

## Our goal

I will teach you how a program can choose what to do based on information it receives.

## What I will teach

An `if` statement runs code when a condition is true. `else` gives us another path. We can compare values with operators such as `>`, `<`, `>=`, `<=`, `==`, and `!=`. For several categories, we can use an `if`/`else if` chain. A `switch` can be useful when we are selecting among specific whole-number or character choices.

We will agree on the exact rules before writing the comparisons. For example, if an A begins at 90, the rule should include 90 (`>= 90`).

## Guided steps

1. Write a program that asks for a temperature.
2. Decide what message should appear for temperatures above 100 and what message should appear otherwise.
3. Add an `if`/`else if` chain for a simple scale: 90 and above is A, 80 and above is B, 70 and above is C, otherwise F.
4. Test boundary values: `89`, `90`, `79`, `80`, and `70`.
5. Explain why the most specific/highest threshold should be checked first.

## Practice

- Ask for a number and report whether it is positive, negative, or zero.
- Ask how many points a learner earned and assign a letter grade using agreed-upon boundaries.
- Add a message for invalid scores below 0 or above 100. In Lesson 9, we will make invalid input ask again rather than simply report it.

## Check for understanding

- What is a condition?
- What is the difference between `=` and `==`?
- Why do we test values exactly on the grade boundaries?

## Source connection

`Feb9` introduces temperature decisions, while `Feb14` uses `switch` to label scores. Later grade-report programs use nested decisions to assign letter grades. We will be explicit about boundary values so a score such as 90 is handled correctly.
