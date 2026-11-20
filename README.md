# Character Scrolling in C

## About This Project

This is a simple C programming project that demonstrates how to use **arrays, pointers, functions, and nested loops** to manipulate and display characters.

The program takes an array of characters and prints the word in a rotating sequence by moving the starting position one character forward on each line.

## How It Works

1. A character array stores the word `Letters`.
2. The program calculates the size of the array using `sizeof()`.
3. The `characterScroll()` function receives the character array and its size.
4. Nested `for` loops print the characters in a different order on each line.
5. Pointer arithmetic is used to access individual characters.

## Example Output

```text
Letters
ettersL
ttersLe
tersLet
ersLett
rsLette
sLetter
Letters
```

## Concepts Practised

- **Arrays:** Storing multiple characters.
- **Pointers:** Accessing array elements through memory addresses.
- **Pointer Arithmetic:** Using `*(characters + j)` to access characters.
- **Functions:** Passing an array and its size to a function.
- **Nested Loops:** Controlling the order in which characters are printed.
- **sizeof Operator:** Calculating the number of elements in an array.

## Technologies Used

- C Programming Language
- Visual Studio Code
- GCC / Clang Compiler

## Learning Objective

The aim of this project is to improve my understanding of pointers, arrays, and nested loops in C programming.

It also helps me practise writing reusable functions and working with character arrays.
