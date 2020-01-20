```c
1 | char *ptr1;
2 | printf("%d %d", sizeof(ptr1), sizeof(*ptr1));
3 | 
```

## What is the output of the above C code snippet? //This question is compiled on 32 bit DEV-C++

KSAs: 255, 262

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 1 1 | 2 2 | ***4 1*** | 4 4 |


Feedback:

- The sizeof operator determines the size of a data type (number of bytes). For the first sizeof(ptr1) it is determining the size of the pointer, which is 4 bytes. The second, sizeof(*ptr) dereferences the pointer so it determines the size of a char, which is 2 bytes

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

