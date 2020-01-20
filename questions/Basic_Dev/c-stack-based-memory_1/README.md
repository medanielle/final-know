```c
1 | int *ptr1 = malloc(sizeof(int));
2 | 
```

## Where is ptr1 stored?

KSAs: 262, 294, 295, 296

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| Cache | ***The stack*** | The heap | None of the above |


Feedback:

- While the memory allocated by the expression "malloc(sizeof(int))" is allocated on the heap, the pointer "ptr1" that holds that address is allocated on the stack at compile time

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

