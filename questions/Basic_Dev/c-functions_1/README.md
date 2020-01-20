```c
1  | void main()
2  | {
3  |    fun(3);
4  | }
5  | 
6  | void fun(int n)
7  | {
8  |    for(int i = n;i > 0; i--)
9  |      printf("GeeksQuiz");
10 | }
11 | 
```

## Why does the above program cause a compile error?

KSAs: 256

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| The code has a syntax error in for loop header. | ***fun in the main function has yet to be defined.*** | fun is an invalid function name. | n is not initialized in the for loop header. |


Feedback:

- A) Incorrect: the syntax if the for loop is correct
- B) Correct: fun is yet to be defined when the compiler encounters it on line 3. It is necessary to define a prototype above main so the definition is known
- C) Incorrect: fun is a valid name for a function
- D) Incorrect: n is intialized when the function is called

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

