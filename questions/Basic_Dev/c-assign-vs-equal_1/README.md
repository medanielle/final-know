```c
1 | int x = 5;
2 | if(x = 3)
3 |    printf("it is equal");
4 | else
5 |    printf("it is not equal");
6 | 
```

## Given the above C code snippet, what is the problem?

KSAs: 266

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***3 is being assigned to x instead of compared.*** | if statements require curly braces if there is an else. | printing strings require a %s specifier. | the code is logically correct. |


Feedback:

- A) Correct: the correct syntax for comparison should be x == 3 vs. x = 3
- B) Incorrect: if statements do not require curly braces if they contain only one statement in their body
- C) Incorrect: specifiers are optional for the printf function

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

