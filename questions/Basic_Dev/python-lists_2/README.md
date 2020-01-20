```python
1 | values = [[3, 4, 5, 1], [33, 6, 1, 2]]
2 | 
3 | for row in values:
4 |     row.sort()
5 |     for element in row:
6 |         print(element, end = "  " )
7 | 
```

## What will be the output of the above Python code snippet?

KSAs: 32, 80

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| 3 4 5 1 33 6 1 2 | 3 4 5 1 33 6 1 2 | 1 1 2 3  4 5 6 33 | ***1 3 4 5 1 2 6 33*** |


Feedback:

- Line 1 declares a list of lists where each element in the list is a list itself. With this in mind, Line 3 loops through the outter list putting the inner lists in row and line 4 sorts the inner list. Line 5 loops through each item in the inner list and line 6 prints each item, changing the default line ending character to a space. The correct output is 1 3 4 5 1 2 6 33.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

