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

## Which of the following variables contain a memory address?

KSAs: 262

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***p*** | z | y | All the above |


Feedback:

- A) Correct: p is a pointer, and pointers can contain a memory address
- B) Incorrect: z is not a pointer and therefore cannot contain a memory address
- C) Incorrect: y is not a pointer and therefore cannot contain a memory address

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

