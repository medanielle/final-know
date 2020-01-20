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

## Which of the following lines of code contain a type cast?

KSAs: 255, 265

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 4 | 12 | ***25*** | 23 |


Feedback:

- A) Incorrect: Line 4 contains just a preprocessor define statement
- B) Incorrect: Line 12 is a variable declaration and initialization by calling a function
- C) Correct: In line 25 there is a cast indicated by (float). This essential casts the value in numerator (defineds as an int) to a float, so that the resulting division returns a floating point value
- D) Incorrect: Line 23 contains a header to a function definition

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

