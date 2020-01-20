```c
1 | int x = 10;
2 | int y = 3;
3 | 
4 | float z = (float)x/y;
5 | 
```

## Why is a cast necessary in the above code snippet?

KSAs: 255, 265

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| because int cannot be assigned to float variables | ***otherwise floating point precision would be lost in the division*** | float casting is required for int division | to reduce the length of the division result |


Feedback:

- A) Incorrect: int can be assigned to floating point variables
- B) Correct: if x is not cast to a float, x/y would result in int division providing an int result and losing any floating point results. Casting one of the vaiables to a float will result in the equation evaluating to a floating point number
- C) Incorrect: float casting is not required but precision will be lost without it
- D) Incorrect: casting to a float will not reduce the size of the result

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

