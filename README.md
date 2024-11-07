# CS303-Assignment-3
Overview
This project contains three main implementations:

A templated Queue data structure with several utility functions and operations.
A recursive linear search function to find the last occurrence of a target in a vector.
An insertion sort algorithm that sorts a linked list of integers.
Each implementation demonstrates fundamental data structures and algorithms in C++ with practical examples.

Contents
1. Queue Implementation (Q1)
The first implementation defines a templated Queue class that provides basic queue functionalities using a linked list approach.

Features:
push(): Adds an element to the rear of the queue.
pop(): Removes the front element from the queue.
front(): Retrieves the front element without removing it.
size(): Returns the number of elements in the queue.
empty(): Checks if the queue is empty.
display(): Prints all elements in the queue.
move_to_rear(): Moves the front element to the rear of the queue.
Example Usage:
The main() function demonstrates:

Instantiating a queue of integers and pushing 10 values.
Displaying all elements in the queue.
Moving the front element to the rear.

2. Recursive Linear Search (Q2)
This function finds the last occurrence of a target value in a vector using a recursive linear search approach.

Features:
Accepts a vector of integers, a target value, and the starting index.
Recursively searches for the target value.
Returns the index of the last occurrence of the target if found, or -1 if not found.
Example Usage:
The main() function demonstrates:

Searching for the last occurrence of a target integer in a vector.
Displaying the index of the last occurrence or indicating if the target is not found.

3. Insertion Sort for a Linked List (Q3)
This implementation sorts a singly linked list of integers using the insertion sort algorithm.

Features:
append(): Adds a new node with the given value to the end of the linked list.
printList(): Displays the linked list elements.
insertionSort(): Sorts the linked list in ascending order using the insertion sort algorithm.
Example Usage:
The main() function demonstrates:

Creating a linked list with sample integer values.
Sorting the linked list using insertion sort.
Printing the original and sorted lists.
