```c
1 | struct myGrade{
2 |    int a;
3 | };
4 | 
5 | struct myGrade grade1={1};
6 | struct myGrade grade2 = grade1;
7 | 
```

## In the above C code snippet, what is happening on the last line?

KSAs: 346

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| grade2 is created as an alias to grade1 | grade2 is a pointer pointing to grade1 | ***the contents of grade1 is being used to create and initialize grade2*** | grade2 is replacing grade1 in stack memory |


Feedback:

- Similar to any assignment, the contents of the right side variable is used as a copy to populate the contents of the left side variable.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

