```c
1 | struct site
2 | {
3 |    char name[10];
4 |    int no_of_pages;
5 | };
6 | struct site *ptr;
7 | printf("%d ", ptr->no_of_pages);
8 | printf("%s", ptr->name);
9 | 
```

## Why would you receive a compile error for the above snippet of code?

KSAs: 262

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| There is a semi-colon after the struct declaration. | struct pointers do no support the -> operator. | ***ptr hasn't been initialized.*** | pointers cannot be declared for a struct type. |


Feedback:

- A) Incorrect: struct delarations require a semi-colon at the end
- B) Incorrect: all pointer support the -> operator
- C) Correct: On line 6 ptr is declared but never initialized therefore not 'pointing' to anything causing an error during compile.
- D) Incorrect: pointers can be declared for struct types

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

