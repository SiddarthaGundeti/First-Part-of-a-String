# First-Part-of-a-String

Write a program that reads a string and prints the first part of the string that has numbers.

The given string contains 2 parts:
* The first part contains only digits.
* The second part contains only one character.

Example: 10y, 1a

Input: 10y

Output: 10

Approach

Read the input string.
Find the length of the string.
Extract the first part of the string that contains digits.
Convert the first part to an integer.
Print the integer.
Step-by-Step Explanation
Step 1: Read the input string

Read the input string using the input() function and store it in a variable called string.

Step 2: Find the length of the string

Find the length of the string using the len() function and store it in a variable called no_of_characters.

Step 3: Extract the first part of the string

Find the index of the last character in the string by subtracting 1 from the length of the string. Store this value in a variable called end_index.

Extract the first part of the string that contains digits by slicing the string from the beginning to the end_index. Store this value in a variable called number.

Step 4: Convert the first part to an integer

Convert the first part of the string, which is stored in the variable number, to an integer using the int() function.

Step 5: Print the integer

Print the integer value of the first part of the string using the print() function.
