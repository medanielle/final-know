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

## On which line of code is the pointer dereferenced?

KSAs: 262

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 16 | ***18*** | 12 | 14 |


Feedback:

- Line 18 is correct: a pointer is declared by providing a type, followed by a * and a variable name such as:  int *p;  At this point p is a pointer.  To dereference (access the contents of what it points to) the pointer, you use the * as in:  *p.

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

