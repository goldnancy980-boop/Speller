CS50x Speller

A spell-checking program written in C for Harvard University's CS50x course. It uses a hash table and linked lists to identify misspelled words efficiently.

Features
Loads dictionary words into memory.
Checks spelling without case sensitivity.
Uses a hash table for efficient word lookup.
Manages memory through dynamic allocation and deallocation.
Reports misspelled words and performance statistics.

Project Structure

dictionary.c — Implements dictionary functions.
dictionary.h — Contains function declarations and constants.
speller.c — Main spell-checker program.
Makefile — Compilation instructions.
texts/ — Sample text files.
keys/ — Expected output files.

Technologies

C
CS50 Library
Hash Tables
Singly Linked Lists
Dynamic Memory Allocation

Compilation
make speller

Usage
Check a text file using the default dictionary:
./speller texts/lalaland.txt
Specify a dictionary manually:
./speller dictionaries/large texts/lalaland.txt

key concepts 

Data structures, algorithms, file handling, string manipulation, and memory management.
