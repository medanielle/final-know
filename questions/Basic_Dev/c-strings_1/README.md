```c
1 | char name[]="Cppbuz";
2 | int len;
3 | int size;
4 | len = strlen(name);
5 | size = sizeof(name);
6 | printf("%d,%d",len,size);
7 | 
```

## What is the output of the above C code snippet?

KSAs: 255, 263, 555

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 6,6 | ***6,7*** | 7,7 | 0,0 |


Feedback:

- When creating a char array with a string literal: char name[]="Cppbuz";  the array size is determined by the number of characters in the array plus an addition null character \0 that is provided by default.  strlen will return the number of characters in the char array (not including the \0), sizeof for an array will provide the number of elements occupied by data including the last element of \0, therefor the first value is 6 and the second value is 7

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

