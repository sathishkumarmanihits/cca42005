# cca42005

1.	Given ‘n’ integers, write an algorithm and the subsequent Python code to print all numbers that are isomorphic to the first number. Two numbers are said to be isomorphic if they have the same number of digits in it and the sets of positions having the same digits are equal.. For example:
•	12321 is isomorphic to 83538.
Both the numbers are of length five. In 12321, positions 2 and 4 have the same digit 2, Positions 1 and 5 have same digit 1. Hence the set of positions having the same digit are {{1, 5}, {2, 4}. Similarly, for the number 83538, the set of positions having the same digit is {{1, 5}, {2, 4}}.
•	1232 is not isomorphic to 2342 because set of places having same digits for 1232 is {{2, 4}} and for 2342 is {{1, 4}} (digits are numbered from left to right starting from 1).
•	12 not isomorphic to 10
•	. If none of the numbers are isomorphic then print ‘No isomorphic’. Input Format
First line contains the number of elements, n Next ‘n’ line contains the numbers
Output Format
Print first number in the first line
Next few lines contain the numbers that are isomorphic to first number.
