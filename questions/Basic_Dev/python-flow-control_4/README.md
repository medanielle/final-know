```python
1 | values = [3, 5, 7, 9, 11, 13, 15]
2 | 
3 | for i in range(2, len(values), 2):
4 |     print (values[i])
5 | 
```

## What is the output for the above Python code snippet?

KSAs: 32, 80

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| 5<br>7 | 7<br>9<br>11<br>13<br>15 | 7<br>11 | ***7<br>11<br>15*** |


Feedback:

- Looking at line 3, the range input parameters are as follows, from left to right: starting index (inclusive), ending index (non-inclusive), and step. Therefore, the loop starts at index 2, goes the entire length of the list, and steps by 2. So the first value accessed is 7 (at index 2), then step 2 to the next value of 11 (at index 4), then step 2 to the final value of 15 (at index 6).

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

