```c
1 | int x = 10;
2 | int *y = &x;
3 | (*y)++;
4 | x++;
5 | printf("%d\n",*y);
6 | printf("%d\n",x);
7 | 
```

## Given the above C code snippet, what is the output or result?

KSAs: 255, 262

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 11<br>11 | ***12<br>12*** | 11<br>12 | 12<br>11 |


Feedback:

- Line 1 x is initialized to 10, Line 2 y is a pointer that gets intialized to the address of x. Line 3 y is dereferenced (contents of x) and incremented 1 so x now contains 11. Line 4 x is incremented to 12, Line 5 prints the dereference of y (contents of x), and line 6 prints x.  Both print statements print 12

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

