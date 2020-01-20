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

## Which line of code contains a function prototype?

KSAs: 256

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 10 | ***6*** | 12 | 19 |


Feedback:

- A) Incorrect: Line 10 is calling (invoking) an existing library function rand()
- B) Correct: a function prototype is a single line typically at the top of the program that provides the signature for a function to be defined later
- C) Incorrect: Line 12 is calling (invoking) an the function getQuotient
- D) Incorrect: there is no code on this line

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

