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

## What would happen if on line 12 you passed two floats instead of two ints?

KSAs: 255, 256, 257, 265

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| The values passed would be floating point numbers | ***The values passed would be truncated and passed as integers*** | The values would be rounded to the nearest int and passed | Compile error |


Feedback:

- The floating point numbers would be automatically typecasted into ints by the compiler since the prototype on line 6 declares 2 int parameters. Casting a float to an int causes the value after the decimal point to be truncated and a loss of that information.

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

