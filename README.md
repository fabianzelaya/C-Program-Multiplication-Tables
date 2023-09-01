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


## Tables

### Table 1
|   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | 11  | 12  |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 | 12 |
| 2 | 2  | 4  | 6  | 8  | 10 | 12 | 14 | 16 | 18 | 20 | 22 | 24 |
| 3 | 3  | 6  | 9  | 12 | 15 | 18 | 21 | 24 | 27 | 30 | 33 | 36 |
| 4 | 4  | 8  | 12 | 16 | 20 | 24 | 28 | 32 | 36 | 40 | 44 | 48 |
| 5 | 5  | 10 | 15 | 20 | 25 | 30 | 35 | 40 | 45 | 50 | 55 | 60 |
| 6 | 6  | 12 | 18 | 24 | 30 | 36 | 42 | 48 | 54 | 60 | 66 | 72 |
| 7 | 7  | 14 | 21 | 28 | 35 | 42 | 49 | 56 | 63 | 70 | 77 | 84 |
| 8 | 8  | 16 | 24 | 32 | 40 | 48 | 56 | 64 | 72 | 80 | 88 | 96 |
| 9 | 9  | 18 | 27 | 36 | 45 | 54 | 63 | 72 | 81 | 90 | 99 | 108 |
| 10| 10 | 20 | 30 | 40 | 50 | 60 | 70 | 80 | 90 | 100| 110| 120|

### Table 2
|   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | 11  | 12  |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 2  | 4  | 6  | 8  | 10 | 12 | 14 | 16 | 18 | 20 | 22 | 24 |
| 2 | 4  | 8  | 12 | 16 | 20 | 24 | 28 | 32 | 36 | 40 | 44 | 48 |
| 3 | 6  | 12 | 18 | 24 | 30 | 36 | 42 | 48 | 54 | 60 | 66 | 72 |
| 4 | 8  | 16 | 24 | 32 | 40 | 48 | 56 | 64 | 72 | 80 | 88 | 96 |
| 5 | 10 | 20 | 30 | 40 | 50 | 60 | 70 | 80 | 90 | 100| 110| 120|
| 6 | 12 | 24 | 36 | 48 | 60 | 72 | 84 | 96 | 108| 120| 132| 144|
| 7 | 14 | 28 | 42 | 56 | 70 | 84 | 98 | 112| 126| 140| 154| 168|
| 8 | 16 | 32 | 48 | 64 | 80 | 96 | 112| 128| 144| 160| 176| 192|
| 9 | 18 | 36 | 54 | 72 | 90 | 108| 126| 144| 162| 180| 198| 216|
| 10| 20 | 40 | 60 | 80 | 100| 120| 140| 160| 180| 200| 220| 240|

<!-- Continue with tables for numbers 3 to 10 -->

You can continue this pattern to create tables for numbers 3 to 10 as well. This Markdown format can be used in your GitHub README file to display the multiplication tables.


## Thanks for watching!

If you like my code then follow me on my social media. Thank you!

[![](https://img.shields.io/badge/github-39d353?style=for-the-badge)](https://github.com/fabianzelaya)
[![](https://img.shields.io/badge/twitter-1D9BF0?style=for-the-badge)](https://twitter.com/fabianzelayahn)
[![](https://img.shields.io/badge/linkedin-0033FF?style=for-the-badge)](https://www.linkedin.com/in/fabianzelaya/)
[![](https://img.shields.io/badge/instagram-blueviolet?style=for-the-badge)](https://www.instagram.com/fabianzelayahn/)
[![](https://img.shields.io/badge/tiktok-fe2c55?style=for-the-badge)](https://www.tiktok.com/@fabian.zelayahn)
[![](https://img.shields.io/badge/fabianzelaya.com-lightgrey?style=for-the-badge)](http://www.fabianzelaya.com/)
<!--[![](https://img.shields.io/badge/fabianzelaya.com-orange?style=for-the-badge)](https://www.fabianzelaya.com/)-->

<img src="https://ucarecdn.com/e15865bd-4124-458b-98f3-eb56907e7097/FZ_Signature.svg" width="240" height="79.63" />
