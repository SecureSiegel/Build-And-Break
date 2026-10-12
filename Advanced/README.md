# Year 2 C++: From Functions to Objects

Welcome back! In Year 1 we learned how to plan a program and build it with variables, decisions, loops, functions, arrays, and files. In this course, I will help you take the next step: organize a program around data and the objects that work with that data.

These lessons are based on the material in the sibling `Year2Projects` folder. The examples are from an older Visual C++ course, so I will teach the underlying ideas using modern standard C++ where possible. The old Windows Forms projects use Microsoft C++/CLI, which is a Windows-specific technology; I will treat those projects as historical examples of event-driven programming, not as a portable C++ setup.

## How I will teach this course

Work through the lessons in order. In every lesson, we will:

1. Read the goal and agree on what the program or class should do.
2. Sketch the data and the steps before coding.
3. Follow the guided steps and run small tests as we build.
4. Try the practice tasks and explain our design choices.
5. Use the check-for-understanding questions before moving forward.

Errors are part of learning. We will read compiler messages, test boundary cases, and correct mistakes instead of assuming old sample code is always right.

## Course sequence

| Lesson | What we will learn | Source-project connection |
|---|---|---|
| [01 - Review, Program Design, and Debugging](Lesson-01-Review-Program-Design-and-Debugging.md) | Plan the problem, specify input/output, build, test, document, and debug | `Aug31`, `Sept5c` |
| [02 - Arrays, Functions, and References](Lesson-02-Arrays-Functions-and-References.md) | Pass arrays to functions, use bounds safely, and change values through references | `Sept5`, `Sept7`, `Aug31` |
| [03 - Pointers and Addresses](Lesson-03-Pointers-and-Addresses.md) | Understand addresses, dereferencing, null pointers, and safe pointer use | `Sept7/Pointer Sample`, `Aug31` |
| [04 - Classes and Encapsulation](Lesson-04-Classes-and-Encapsulation.md) | Design a class with private state, public operations, and constructors | `Sept12/Fraction Class Example`, `Sept14/Goldfish` |
| [05 - Header Files, Implementation, and Client Code](Lesson-05-Header-Implementation-and-Client-Code.md) | Separate a class declaration, definitions, and the code that uses it | `Sept12`, `Sept14`, `Prog1/Inventory` |
| [06 - Building Useful Classes](Lesson-06-Building-Useful-Classes.md) | Model inventory or sports data, validate state, and calculate derived values | `Prog1/Inventory`, `Sept14HW/Rugby`, `Program2` |
| [07 - Object Lifetimes and Destructors](Lesson-07-Object-Lifetimes-and-Destructors.md) | Understand constructors, destructors, scope, and resource ownership | `Sept21/Bookstore`, `Oct5/Homework` |
| [08 - Linked Lists and Dynamic Data](Lesson-08-Linked-Lists-and-Dynamic-Data.md) | Connect nodes, traverse a list, and reason about insertion, removal, and cleanup | `MIDTERM SAMPLE`, `MIDTERM MIDTERM MIDTERM` |
| [09 - Event-Driven Programs and the Final Project](Lesson-09-Event-Driven-Programs-and-Final-Project.md) | Understand GUI events, plan a small object-based project, test it, and present it | `Sept28/Windows Program`, `Program 2`, `Program 3 Sample`, `FINAL SAMPLE` |

## Modern C++ and the historical projects

Some original files use `void main()`, fixed-size character arrays, `strcpy_s`, global `using namespace std`, raw owning pointers, or older Visual Studio project files. We will learn from the concepts without treating every historical implementation as a safe pattern to reuse. Our examples will prefer `int main()`, `std::string`, clear ownership, and standard library tools where they fit.

The old C++/CLI Windows Forms projects depend on Microsoft's Windows toolchain. If we study them, I will focus on the transferable idea that a user action triggers an event handler. We will not assume those projects build in a standard C++ compiler or on another operating system.

## What I want you to be able to do

By the end, you should be able to explain how an object protects its data, how its functions use that data, how separate source files fit together, and how a collection of dynamically connected nodes differs from an array. I also want you to be able to test and explain your own design with confidence.
