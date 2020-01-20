```python
1 | values = [2, 3, 4, 6, 7, 9, 12, 18]
2 | 
3 | for i in range(2, 7):
4 |     if values[i] % 2 == 0 and values[i] % 3 == 0:
5 |         print (values[i])
6 | 
```

## What is the output for the above Python code snippet?

KSAs: 32, 60

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 4<br>6<br>9<br>12 | ***6<br>12*** | 4<br>12 | 3<br>6<br>7 |


Feedback:

- Since two parameters passed to the range function set the inclusive starting and non-inclusive ending values, the loop on line 3 starts at index 2 and goes to index 6, stepping 1 after each iteration. Line 4 checks to see if the value is a multiple of 2 and 3, making it an effective multiple of 6. Therefore, the output is 6 and 12 on their own line.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

