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

## How many elements are in the array pointed to by p?

KSAs: 262, 263

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***10*** | 40 | 80 | 8 |


Feedback:

- The malloc command will allocate 40 bytes of memory: y = 10 and sizeof(float) = 4. However, becasue p is a float pointer, the array will be partition into 4 byte elements resulting in a 10 element array

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

