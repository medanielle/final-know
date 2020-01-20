```python
1 | values = []
2 | 
3 | for i in range(10):
4 |     values.append(i * 2)  
5 | for i in range(3, len(values)-3):
6 |     print (values[i])
7 | 
```

## What is the output for the above Python code snippet?

KSAs: 32, 80

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***6<br>8<br>10<br>12*** | 6<br>8<br>10<br>12<br>14 | 4<br>6<br>8<br>10<br>12 | 3<br>4<br>5<br>6 |


Feedback:

- The values list starts out empty in line 1 but is then filled with values in lines 3 and 4. Since a single parameter in the range function is non-inclusive, and begins at 0 and steps one by default, the sequential numbers 0 - 9 are accessed in line 3 and each one is multiplied by 2 and appended to the values list in line 4. When line 5 is reached, values = [0, 2, 4, 6, 8, 10, 12, 14, 16, 18]. Keeping in mind that passing two parameters into range sets the inclusive starting and non-inclusive ending range values, the loop starts at 3 and goes to the length of values minus 3; 10 total values minus 3 is 7, so the 6th index is the last one accessed. The final printed output is 6, 8, 10, and 12; all on their own line.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

