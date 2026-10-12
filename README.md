# Year 1 C++: Learn It, Build It, Use It

Welcome! I put this course together from the programming work in `Year1Projects`. We will begin with small programs, learn one idea at a time, and then combine those ideas in a student-grade report project.

This course is for learners of different ages who are new to programming. No previous coding experience is needed. I want everyone to ask questions, test ideas, learn from mistakes, and be proud of steady progress.

## How to use these lessons

Work through the lessons in order. For each lesson:

1. Read the goal together and talk about what the program should do.
2. Follow the guided steps. Type and run the code in small pieces instead of copying a whole program without understanding it.
3. Try the practice tasks independently, then compare approaches.
4. Use the check-for-understanding questions to decide whether we are ready to move on.

Each lesson has a suggested source-project connection. Those folders and files are in the sibling `Year1Projects` folder. The original work is useful historical course material, but it was written for an older C++ environment. I will teach modern, standard C++ in our new programs.

## Course sequence

| Lesson | What we will learn | Source-project connection |
|---|---|---|
| [01 - How a C++ Program Works](Lesson-01-How-a-Program-Works.md) | Program structure, output, comments, and a first run | `Jan12`, `Jan17` |
| [02 - Variables, Input, and Calculations](Lesson-02-Variables-Input-and-Calculations.md) | Types, keyboard input, arithmetic, and checking formulas | `Jan17`, `Jan19`, `ASSIGNMENT 1` |
| [03 - Text and Clear Output](Lesson-03-Text-and-Clear-Output.md) | Strings, combining text, and readable numeric output | `Jan24`, `Jan26`, `ASSIGNMENT 1` |
| [04 - Making Decisions](Lesson-04-Making-Decisions.md) | Comparisons, `if`/`else`, multi-way choices, and grade rules | `Feb9`, `Feb14`, `Feb16` |
| [05 - Repeating Work with Loops](Lesson-05-Repeating-Work-with-Loops.md) | `while` and `for` loops, counters, sentinels, and safe exits | `Feb14`, `Feb21`, `Mar16` |
| [06 - Reusable Functions](Lesson-06-Reusable-Functions.md) | Prototypes, parameters, return values, and references | `Mar14`, `Mar16`, `Mar21` |
| [07 - Reading and Writing Text Files](Lesson-07-Reading-and-Writing-Text-Files.md) | File streams, record formats, error checks, and output files | `Feb2`, `Feb16`, `Apr4` |
| [08 - Collections with Arrays](Lesson-08-Collections-with-Arrays.md) | One- and two-dimensional arrays, indexing, and nested loops | `Mar23`, `Mar28`, `Apr4` |
| [09 - Building a Grade Report in Stages](Lesson-09-Building-a-Grade-Report-in-Stages.md) | Input validation and combining files, arrays, functions, and calculations | `Program Assignment 1-4`, `Apr4` |
| [10 - Structs and the Grade-Report Capstone](Lesson-10-Structs-and-the-Grade-Report-Capstone.md) | Grouping student data, processing records, and producing a report | `Program Assignment 5`, `Apr6` |
| [11 - Strings, Review, and Portfolio](Lesson-11-Strings-Review-and-Portfolio.md) | Text records, debugging, review, and presenting finished work | `FINALS`, `Screenshots`, `PORTFOLIO.TXT` |

The original course included repeated practice, quizzes, assignments, a midterm, and a final. I have kept that rhythm: use the practice tasks and checks as low-pressure reviews, and treat Lessons 9-11 as opportunities to bring earlier skills together.

## A note about the original code

Many source programs use `void main()`, `<conio>`, `getch()`, or `clrscr()`. These belong to old compiler-specific environments and are not portable standard C++. In this course, I will use `int main()`, standard headers such as `<iostream>` and `<string>`, and ordinary console input/output. I will also show learners how to recognize a bug, test a small example, and correct it rather than treating every old line as a rule to copy.

## Materials and teaching approach

- A C++ compiler or beginner-friendly IDE that supports standard C++.
- A text editor and a place to save lesson programs.
- Paper or a whiteboard for sketching the input, steps, and expected output before coding.
- Patience and a willingness to try again. Errors are information we can use.

I will keep examples small, invite learners to predict what they will do, and encourage them to explain their choices in their own words. The goal is not just to make a program run; it is to understand how to make a clear plan and turn it into working code.
