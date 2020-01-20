```c
1 | int x = 1;
2 | 
3 | x = x>>2;
4 | 
5 | printf( "%d ", x );
6 | 
```

## What is the output of the above C code snippet?

KSAs: 292

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 4 | 2 | ***0*** | 1 |


Feedback:

- x is initialized to 1 (binary 00000001). Line 3 does a bit shift of two to the right so now all bits are zero (0), thus resulting in an int value of 0

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

