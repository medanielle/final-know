```c
1 | int values [] = {1, 2, 3, 4, 5};
2 | 
3 | printf("%d",*values);
4 | 
```

## Given the above C snippet, what is the output or result?

KSAs: 262, 263

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| syntax error | run-time error | ***1 is printed*** | prints address of array |


Feedback:

- An array name contains the address of the first element (base address) of an array, therefore dereferencing the array name *values will give the contents of that first element.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

