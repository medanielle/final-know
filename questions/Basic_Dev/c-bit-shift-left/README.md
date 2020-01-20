```c
1 | int x = 2; 
2 | x <<= 1;
```

## What is the value of x after the C program snippet above executes?

KSAs: 291

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 2 | 1 | ***4*** | 0 |


Feedback:

- Left shift operator shifts bits one to the left.  Given the start bits were 00000010 for a value of 2, when shifting the bits one to the left the result is 00000100 resulting in 4

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

