# C Program Multiplication Tables
A C program that generates multiplication tables from 1 to 10 up to a specified maximum value.

This C program generates multiplication tables for numbers from 1 to 10 up to the value of 12. Here's a breakdown of what it does:

```c
#include <stdio.h>  // Include the standard input-output library for printf.

int main() {
    int i, j;       // Declare integer variables i and j.
    int table = 10; // Set the value for the multiplication tables up to 10.
    int max = 12;   // Set the maximum value for each table (up to 12).

    // Outer loop: Iterate through numbers from 1 to 10 for multiplication tables.
    for (i = 1; i <= table; i++) {
        // Inner loop: Multiply the number (i) with values from 0 to 12.
        for (j = 0; j <= max; j++) {
            printf("%d x %d = %d\n", i, j, i * j); // Print the multiplication equation.
        }
        printf("\n"); // Print a blank line to separate tables.
    }

    return 0; // Return 0 to indicate successful program execution.
}
```

Here's what this program does:
* It includes the standard input-output library for using the printf function.
* The program uses two nested for loops:
    * The outer loop (controlled by i) runs from 1 to 10, generating multiplication tables for numbers 1 through 10.
    * The inner loop (controlled by j) runs from 0 to 12, calculating the product of i and j and printing the result in the format "i x j = result."
* After each multiplication table is printed, the program inserts a blank line to separate the tables for better readability.

The program will produce a series of multiplication tables, from 1x0 to 10x12, each with a blank line between them.
