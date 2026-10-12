# Lesson 08 - Linked Lists and Dynamic Data

## Our goal

I will teach you how linked-list nodes point to other nodes, how to traverse a list, and how to reason about insertion, removal, and memory ownership.

## What I will teach

A linked list is a chain of nodes. Each node stores data and a link to the next node. The head pointer identifies the first node; an empty list has no head. Unlike an array, the elements are not required to be stored next to one another in memory.

Creating nodes dynamically means someone must own them and release them. We will draw the links before coding and keep a clear rule for who deletes each node. For modern application code, standard containers are usually preferable; the linked list is useful here for understanding pointers and data-structure tradeoffs.

## Guided steps

1. Draw a head pointer and three nodes, each with data and a next link. Mark the final link as `nullptr`.
2. Write a traversal loop that visits each node until the current pointer is null.
3. Add one node at the front and update the head.
4. Trace the list after every pointer update. Do not lose the link to the rest of the list.
5. Design a removal operation and identify which node must be deleted and which links must be updated.
6. Test an empty list, a one-node list, and a multi-node list. Check that every allocated node is released.

## Practice

- Add a function that counts the nodes.
- Add an operation that searches for a value.
- Compare a linked list with `std::vector` for indexed lookup and adding elements.

## Check for understanding

- What does the head pointer identify?
- How does traversal know when it has reached the end?
- Who is responsible for releasing a dynamically allocated node?

## Source connection

The `MIDTERM SAMPLE` `LinkedListSample.cpp` introduces a node with data and a next pointer. The midterm and final folders include related examples. Some sample files are incomplete or malformed; we will diagram and test each operation rather than copy them uncritically.
