# Lesson 01 - How a C++ Program Works

## Our goal

I will help you recognize the basic shape of a C++ program, display a message, and run a small program successfully.

## What I will teach

A program is a set of instructions the computer follows in order. We will use `main` as the place where our program begins, `cout` to display text, and comments to leave notes for people reading the code.

We will write portable C++ from the start. A modern beginner program uses `int main()` and `#include <iostream>`. Some old course examples use `void main()` and `getch()`; those are not the standard pattern we will use.

## Guided steps

1. Create a new file named `hello.cpp`.
2. Type this program, then save it:

   ```cpp
   #include <iostream>

   int main() {
       std::cout << "Hello, C++!" << '\n';
       std::cout << "I am learning to write programs." << '\n';
       return 0;
   }
   ```

3. Before running it, point to the include, the start of `main`, each output instruction, and the closing brace.
4. Run the program. Compare the screen with your prediction.
5. Change the message and run it again. Add a comment with `//` describing what the program does.

## Practice

- Print your name or a name you invent, then print one thing you hope to learn.
- Add a third output line and predict where it will appear.
- Remove one semicolon, run the program, and read the compiler message. Put the semicolon back. We are learning how to use error messages, not trying to memorize every message.

## Check for understanding

- Where does our program begin?
- What does `std::cout` do?
- Why do we save and run after making a small change?

## Source connection

The early `Jan12` and `Jan17` programs introduce console output and a main function. Their ideas are still useful; I will update the older compiler-specific syntax as we practice.
