```c
1 | struct score{
2 |    int a;
3 | };
4 | 
```

## For the above struct declaration, which is the proper way to declare a variable for the struct?

KSAs: 14, 24, 28

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| int score; | ***struct score myScore;*** | score.a = 100; | score myScore; |


Feedback:

- The proper syntax to declare a variable for a struct is: the keyword 'struct' followed by the struct name (score), followed by the variable name (myScore)

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

