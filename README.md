# Build-And-Break
Build applications with C++ and then learn how they work through reverse engineering


# Why I Created These C++ Course Folders

## The purpose

I created these folders to turn my Year 1 and Year 2 C++ coursework into a clear path for learning how to code with C++. The original projects give us examples and history; the `Ready` folders turn those ideas into lessons we can follow, practice, and build on.

My goal is to help learners understand how to plan a program, write it, test it, improve it, and explain how it works. We will build confidence one small idea at a time. Mistakes are part of learning, and we will use them to get better.

## What the course folders contain

- [`Year1Projects`](Year1Projects/) contains the organized Year 1 lessons, from first programs and calculations through a student-grade-report project, moving from functions, arrays, and pointers into classes, object lifetimes, linked lists, and event-driven programs.


## How we will learn

In each lesson, I will explain the goal, model the new idea, and guide learners through building and testing a program. Then learners will try practice tasks and explain their reasoning. By the end of Year 1, we will combine fundamentals into complete small programs. In Year 2, we will organize related information and behavior into objects and explore how larger applications are structured.

I want learners to leave with more than code that happens to run. I want them to be able to describe the problem, make a plan, choose a design, test it with evidence, and explain their decisions to someone else.

## From C++ source code to the machine layer

Learning how a program works does not have to stop at the C++ source. Once we understand how to write and build a small program, I will also introduce the idea of examining what the compiler produced. This is called **reverse engineering**: studying a program or its compiled output to understand its structure and behavior.

With an application we wrote and compiled ourselves, we can use tools such as **Ghidra** to explore the compiled program. We can compare a small C++ function with its disassembly, look at how functions call one another, and observe how source-level ideas are represented as lower-level instructions. We will treat the decompiler's output as an interpretation to investigate, not as a perfect copy of the original source.

This will be a learning activity using our own programs or other software we have clear permission to examine. We will not use these techniques to bypass protections, access data without permission, or interfere with someone else's software or systems.

### How this connects to “How a Program Works”

Our first program will give us a starting point for this larger picture:

1. We write a simple C++ program and explain its instructions.
2. We compile and run it, observing its input, processing, and output.
3. We inspect the compiled version of that same program with an appropriate tool.
4. We compare what we can see at the C++ level with what we can observe at the machine-instruction level.
5. We discuss what stayed recognizable, what the compiler changed, and why the lower-level view is more detailed and less like the source we wrote.

We will keep the first exploration small and guided. The purpose is to connect the ideas we are learning—not to expect beginners to understand every assembly instruction or every feature of a professional reverse-engineering tool at once.

## The bigger goal

I want this course to help learners become curious, capable problem-solvers. We will learn how to create programs, how to reason about their behavior, and how to look beneath the surface when we want to understand more. Step by step, we will connect the code we write to the applications we use and, eventually, to the instructions a computer carries out.
