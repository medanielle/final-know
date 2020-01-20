```c
1 | int x [10];
2 | int *y = malloc(sizeof(x));
3 | 
```

## Given the above C code snippet and given an int is 4 bytes, how many bytes are being allocated for the y pointer?

KSAs: 262, 263

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 4 | ***40*** | 80 | 10 |


Feedback:

- Using sizeof for an array returns the total number of bytes for the array. Given the x is a 10 element array of int, and int is 4 bytes, the total size is 40.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

