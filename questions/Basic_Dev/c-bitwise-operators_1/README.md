```c
1 | printf("%d", 12 & 12);
2 | 
```

## What will be printed in the above code?

KSAs: 287

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 0 | 24 | ***12*** | 1212 |


Feedback:

- The & (and operator) does a bit by bit comparison of each value.  If both bits are 1 then the result is a 1. Because both values are the same, they will have the same bits set to 1 therefore resulting in same binary number of of 00001100

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

