# Lesson 03 - Pointers and Addresses

## Our goal

I will teach you what an address represents, how a pointer stores an address, and how to use a pointer without confusing it with the value it points to.

## What I will teach

A pointer is a variable whose value is an address. The address-of operator `&` asks for an object's address, and the dereference operator `*` accesses the object at that address. A pointer should point to a valid object before we dereference it.

Pointers make some data structures possible, but they also create responsibilities. We will not use uninitialized pointers, dereference null pointers, or keep pointers to objects that no longer exist. For ordinary program data, a reference or a standard container may be safer and clearer.

## Guided steps

1. Create an integer variable and initialize it.
2. Declare a pointer to an integer and initialize it with the variable's address.
3. Print the variable's value, the pointer's stored address, and the value reached by dereferencing the pointer.
4. Change the integer through the pointer and verify that the original variable changed.
5. Set a pointer to `nullptr` and explain why it must not be dereferenced.
6. Draw a box for the integer and an arrow from the pointer to that box.

## Practice

- Write a function that receives an integer pointer and changes the value only when the pointer is not null.
- Compare that function with a reference-parameter version. Discuss which is clearer when a value is always required.
- Identify the risk in dereferencing a pointer that was declared but not initialized.

## Check for understanding

- What does a pointer store?
- What is the difference between `pointer` and `*pointer`?
- What does `nullptr` tell us, and what does it not permit us to do?

## Source connection

The `Sept7/Pointer Sample` demonstrates an address, dereferencing, and modifying a variable through a pointer. The `Aug31` notes introduce pointers alongside arrays and structures. We will keep the useful concepts and avoid unsafe pointer patterns.
