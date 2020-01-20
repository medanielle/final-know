```c
1 | int i,j;
2 | for(i=0,j=0;i<5;i++)
3 | {
4 |    printf("%d%d--",i,j);
5 | }
6 | 
```

## What is the output of the above C code snippet?

KSAs: 266

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 0--01--12--23--34-- | ***00--10--20--30--40--*** | Nothing is printed | 00--01--02--03--04-- |


Feedback:

- In each iteration, two values are printed followed by --, the value for i and the value for j. In the for loop header i is incremented after each iteration whereas j is never modified. So, the first iteration i=0 and j=0, the next iteration i=1 but j is still = 0, etc.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

