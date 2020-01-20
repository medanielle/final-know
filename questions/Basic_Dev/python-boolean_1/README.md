```python
1 | x = 19/2
2 | value = x % 3 == 0
3 | 
4 | if value:
5 |     print (value, " is true")
6 | else:
7 |     print (value, " is false")
8 | 
```

## What is the output for the above Python code snippet in Python 3?

KSAs: 59, 60

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| value is false | ***False is false*** | value is true | True is true |


Feedback:

- Since value is a variable, the output will either be 'True is true' or 'False is false'. Looking at line 2, value becomes the comparison result of x modulus 3 equals 0. Since line 1 becomes 9.5 after division then value turns out to be 9.5 % 3 = 2, which doesn't equal 0 so it's False. The print statement outputs False is false.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

