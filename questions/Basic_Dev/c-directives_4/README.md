```c
1 | #define R 10
2 | #define C 20
3 | 
4 | int* p [R][C];
5 | 
```

## In the above C code snippet, what is p?

KSAs: 14, 24, 28

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***a two-dimensional array of int pointers*** | a pointer to a two-dimensional array of int | a pointer to heap memory of 200 bytes | none of the above |


Feedback:

- A) Correct: p is defined as a 10 X 20 array using the named constants. The type of array is defined by the int* meaning integer pointer
- B) Incorrect: in order for p to be a pointer to an array, the array would need to be declared dynamically using malloc
- C) Incorrect: any heap memory must be declared dynamically using malloc

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

