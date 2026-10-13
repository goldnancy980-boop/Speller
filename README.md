 # CS50 Speller

## Description

**Speller** is a C programming project from Harvard University's **CS50x** course. The program implements a spell-checker that identifies misspelled words in a text using a dictionary.

## How It Works

1. Loads words from a dictionary into a hash table.
2. Uses a hash function to determine where words are stored.
3. Checks text against the dictionary to identify misspelled words.
4. Counts the words loaded, misspelled words identified and other performance statistics.
5. Frees allocated memory when the program finishes.

## Technologies Used

* C
* Hash tables
* Linked lists
* Dynamic memory allocation

## Concepts Learned

* Data structures and algorithms
* Hash functions and collision handling
* Pointers and linked lists
* File handling
* Memory management
* Algorithm efficiency

## How to Run

Compile the program using the provided Makefile:

`make speller`

Run the spell-checker with a text file:

`./speller texts/lalaland.txt`

The dictionary and text file paths may vary depending on the files included in the project.

## What I Learned

This project strengthened my understanding of C programming, data structures, pointers and memory management. It also helped me understand how hash tables and linked lists can be used to build efficient programs.

## Course

Harvard University's CS50x: Introduction to Computer Science.

