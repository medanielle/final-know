```python
1 | a = ['Python', 'is', 'not', 'tough']
2 | for i in range(len(a)):
3 |      print (i, a[i], end=" ")
4 | 
```

## What is the output for the above Python code snippet?

KSAs: 32

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| 1 Python 2 is 3 not 4 tough | Python is not tough | 1 Python 2 is 3 not | ***0 Python 1 is 2 not 3 tough*** |


Feedback:

- Line 2 loops through a range of 0 to the last index in the list. Therefore, line 3's print statement first prints the index number, indicated by the i, and then the value of the requested index in list a, indicated by the a[i]. The end=" " causes a space to be printed instead of the default new line character, which places the entire statement on one line instead of separate lines. The final output is '0 Python 1 is 2 not 3 tough'.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

