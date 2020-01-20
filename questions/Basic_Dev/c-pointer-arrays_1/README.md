```c
1 | int a = 10;
2 | int *c = &a;
3 | printf("%d",c);
4 | 
```

## What is printed for the above code?

KSAs: 255, 262

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 10 | ***the address of a*** | the address of c | Nothing |


Feedback:

- A) Incorrect: in order to print the contents (10) the pointer would have to be dereferenced: *c
- B) Correct: c is defined as a pointer and is being assigned the address of a in line 2, when the c pointer is printed it prints the address of a
- C) Incorrect: in order to print the address of c, it needs to be prepended with an ampersand:  &c

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

