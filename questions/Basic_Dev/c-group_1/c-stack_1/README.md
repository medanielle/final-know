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

## Which of the following variables declare memory in stack memory?

KSAs: 294

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| z | p | denominator | ***All the above*** |


Feedback:

- All variables declared are considered local variable and declare memory on the stack unless they untilize the malloc() function which delares memory on the heap

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

