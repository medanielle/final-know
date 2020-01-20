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

## Which line of code executes the getQuotient function?

KSAs: 256

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 6 | ***12*** | 23 | 25 |


Feedback:

- A) Incorrect: line 6 is the function prototype.
- B) Correct: line 12 float z = getQuotient(x,y) is where the function is called (or invoked)
- C) Incorrect: line 23 begins where the function is defined
- D) Incorrect: line 25 is the last line in the funciton definition

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

