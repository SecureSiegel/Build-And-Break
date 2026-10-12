# Lesson 09 - Event-Driven Programs and the Final Project

## Our goal

I will introduce the event-driven idea behind a graphical program and help you plan, build, test, and present a small object-based final project.

## What I will teach

In a console program, instructions often run from the top of `main`. In an event-driven program, the framework waits for an action, such as a button click, then calls the matching event handler. The handler should validate its inputs, perform a clear task, and show a useful result.

The Year 2 GUI samples use Microsoft's C++/CLI Windows Forms. That toolchain is platform-specific and different from standard C++. We can study the design and event-handler ideas from the samples, but should not assume they compile in a regular cross-platform C++ environment.

## Guided steps

1. Sketch a simple screen for an inventory lookup or fraction calculator.
2. Label the input controls, action button, output area, and exit action.
3. Write down what should happen after each user action.
4. Connect each action to one small handler. Keep calculations in a class or helper function where practical.
5. Validate empty or invalid input and show a clear message.
6. Test normal values, boundary values, and repeated button clicks.
7. Present the project by explaining its purpose, class design, event flow, and tests.

## Practice

- Draw a GUI for the inventory class from Lesson 6.
- Write pseudocode for a button handler that calculates a fraction result.
- Choose either a console implementation in standard C++ or the historical Windows Forms environment available to you. Explain the tradeoffs.

## Check for understanding

- What causes an event handler to run?
- How is event-driven flow different from a simple top-to-bottom console program?
- Why do we validate GUI text before using it as a number?

## Source connection

The `Sept28/Windows Program` sample uses Windows Forms controls and button-click handlers. `Program 2`, `Program 3 Sample`, and `FINAL SAMPLE` contain additional form-based examples. I will teach the transferable interface and event concepts while clearly identifying the older Windows-specific framework.

## Final project checklist

- I can state the problem and intended user.
- I can explain the class or data structure I designed.
- I can explain how input becomes output.
- I have tested normal and edge cases.
- I can show one error I found and how I fixed it.
- I can describe one improvement I would make next.
