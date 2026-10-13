# CS50 Speller

## Description

Speller is a problem set from the CS50 course in which I implemented a spell-checker in C that identifies misspelled words in a text using a dictionary.

## Getting Started

I started this project by downloading the provided starter code as a ZIP file from the official [CS50 Speller problem set page](https://cs50.harvard.edu/x/psets/5/speller/). After downloading and extracting the ZIP file, I opened the project directory in my development environment.

The starter code included the main spell-checking program, header files, a Makefile, dictionaries and text files for testing. Most of the program's structure and functionality had already been provided by CS50. My primary task was to complete the missing implementations in `dictionary.c`.

## Starter Code and My Contribution

CS50 provided the following files and directories:

* **`speller.c`** — The main program that loads a dictionary, checks a text file for misspelled words and displays statistics.
* **`dictionary.h`** — Contains the function declarations required by the dictionary implementation.
* **`Makefile`** — Automates the compilation of the program.
* **`dictionaries/`** — Contains the small and large dictionaries used for testing.
* **`texts/`** — Contains text files used to test the spell-checker.
* **`keys/`** — Contains files used for testing and evaluating the spell-checker.

The main file I worked on was `dictionary.c`, where I completed the `TODO` areas by implementing the functions responsible for loading dictionary words, hashing words, checking spelling, counting dictionary entries and freeing allocated memory.

## How It Works

1. Loads words from a dictionary into a hash table.
2. Uses a hash function to determine where words are stored.
3. Checks text against the dictionary to identify misspelled words.
4. Counts the words loaded, misspelled words identified and other performance statistics.
5. Frees allocated memory when the program finishes.

## Implementation

I implemented the following functions in `dictionary.c`:

* **`load()`** — Loads dictionary words into memory and stores them in a hash table.
* **`hash()`** — Converts a word into a hash value used to determine its position in the hash table.
* **`size()`** — Returns the number of words loaded into the dictionary.
* **`check()`** — Determines whether a word exists in the dictionary, ignoring differences in capitalization.
* **`unload()`** — Frees the dynamically allocated memory used by the dictionary.

## How to Run

### 1. Navigate to the Project Directory

Open the terminal and navigate to the project directory:

```bash
cd Speller
```

### 2. Compile the Program

Compile the program using the provided Makefile:

```bash
make speller
```

### 3. Run with the Small Dictionary

```bash
./speller ..dictionaries/small texts/cat.txt
```

### 4. Run with the Large Dictionary

```bash
./speller ..dictionaries/large texts/lalaland.txt
```

The program checks the specified text file against the selected dictionary and displays misspelled words and performance statistics.

## Testing

I tested the program using both the small and large dictionaries to check its spelling functionality and observe its performance.

## Learning Objectives

* Implement hash tables and linked lists in C.
* Work with pointers and dynamic memory allocation.
* Understand file handling and memory management.

