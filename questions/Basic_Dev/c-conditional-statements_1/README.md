```c
1  | int x = 0;
2  | switch(x) 
3  | {
4  |    case 0: 
5  |      printf("Hello");
6  |    case 1: 
7  |      printf("hi"); 
8  |      break;
9  | }
10 | 
```

## What is the output of the above code snippet?

KSAs: 266

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| Hello | Hi | ***Hellohi*** | Nothing prints |


Feedback:

- This prints Hellohi because although x == 0, there is no break statement in case 0, therefore case 1 is also executed

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

