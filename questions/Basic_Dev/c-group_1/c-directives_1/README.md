```c
1  | #include <stdio.h>
2  | #include <stdlib.h>
3  | 
4  | #define y 10
5  | 
6  | float getQuotient(int, int);
7  | 
8  | int main()
9  | {
10 |     int x = rand();
11 | 
12 |     float z = getQuotient(x,y);
13 |     
14 |     float* p = (float *) malloc(y * sizeof(float));
15 |     
16 |     p[0] = z;
17 |     
18 |     printf("Result is %f", *p);
19 |     
20 |     return 0;
21 | }
22 | 
23 | float getQuotient(int numerator, int denominator)
24 | {
25 |     return (float)numerator/denominator;
26 | }
27 | 
```

## Which line of code contains a preprocessor directive that creates a named constant?

KSAs: 264

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 2 | 10 | ***4*** | 16 |


Feedback:

- A) Incorrect: although line 2 is using a preprocessor directive, it is an include that is used to use other header files in your program
- B) Incorrect
- C) Correct: #define is a preprocessor directive that allows you to create a named constant
- D) Incorrect

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

