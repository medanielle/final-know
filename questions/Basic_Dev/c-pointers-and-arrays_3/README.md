```c
1 | 
2 | char *p = NULL;
3 | 
4 | printf("%c ", *p);
5 | 
```

## Why does the above C code snippet cause a run-time error?

KSAs: 262

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| You cannot initialize a pointer to NULL. | null should be all lower case. | ***You cannot dereference a NULL pointer*** | %c is not a valid specifier |


Feedback:

- Dereferencing a pointer pointing to NULL will cause a run-time error.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

