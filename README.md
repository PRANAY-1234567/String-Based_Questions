Program Name - 
Character Frequency Counter in Python

Description

This program counts how many times each character appears in a given string.
It uses a dictionary to store characters as keys and their frequencies as values.

Code Explanation

A string s is defined ("apple").

An empty dictionary freq is created to store character counts.

The for loop iterates through each character in the string.

freq.get(ch, 0) returns the current count of the character (or 0 if it doesn’t exist).

The count is incremented by 1.

Finally, the dictionary containing character frequencies is printed.

Input
s = "apple"

Output
{'a': 1, 'p': 2, 'l': 1, 'e': 1}

Concepts Used

Strings

Dictionaries

For loop

get() method

Use Case

This program is useful for:

Counting letters in a word or sentence

Basic text analysis

Learning dictionaries in Python
