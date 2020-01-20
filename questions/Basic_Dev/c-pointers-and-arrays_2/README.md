```c
1  | void main()
2  | {
3  |    double scores[20];
4  |    fun(scores);
5  | }
6  | 
7  | void fun(double s[])
8  | {
9  |    // do something here
10 | }
11 | 
```

## For the above C code snippet, what is contained in s?

KSAs: 262, 263

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| First value of the score array | ***Base address of the score array*** | Entire contents of score array | A copy of the entire score array |


Feedback:

- When a function is invoked and provide an array name as an argument, the base address of the array is what is actually passed to the function.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

