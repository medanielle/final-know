```c
1 | const int a = 10;
2 | printf("%d",++a);
3 | 
```

## What is the output of the above C code snippet?

KSAs: 261

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 11 | 10 | ***Compiler error*** | 0 |


Feedback:

- A compiler error will incur because a is declared as a const and any code that attempts to modify a will cause the compiler to error.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

