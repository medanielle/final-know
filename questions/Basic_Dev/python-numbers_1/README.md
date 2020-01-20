```python
1 | numbers = [2, 3, 4, 5, 6]
2 | for x in numbers:
3 |     if x % 2 == 0:
4 |         print (x*x, end = " ")
5 |     else:
6 |         print (x, end = " ")
7 | 
```

## What is the output for the above Python code snippet?

KSAs: 32, 58, 60

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 4 3 9 5 36 | 4 3 16 5 36 7 | ***4 3 16 5 36*** | 2 3 16 5 36 |


Feedback:

- Line 1 creates a sequential list of 5 numbers, starting with 2. Then every number in the list (line 2) is compared to see if that number modulus 2 equals 0 (line 3). Because we are dividing by 2 and comparing the remainder with 0, all even numbers will be True and odd False. If the statement is True then the number squared is printed (line 4); otherwise, just the number is printed (line 6). Both print statements use the space character instead of the 
 character (as seen with end = " "); this causes all numbers to stay on the same line. Therefore, the output is 4 3 16 5 36.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

