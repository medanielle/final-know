```c
1 | int *x = malloc(sizeof(int));
2 | 
```

## In the above statement, where is the memory pointed to by x allocated?

KSAs: 262, 293, 294, 295, 296

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| Stack | Registry | ***Heap*** | Cache |


Feedback:

- Memory allocated at run time is placed on the heap and is done using the malloc() function. Compile time memory is allocated on the stack

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

