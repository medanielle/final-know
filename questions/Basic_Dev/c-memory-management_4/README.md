```c
1 | int x [10];
2 | int *y = malloc(sizeof(x));
3 | 
```

## Given the above C code snippet, where is the memory being allocated with the malloc command?

KSAs: 295

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***heap*** | stack | cache | registers |


Feedback:

- All memory created with malloc is allocated on the heap.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

