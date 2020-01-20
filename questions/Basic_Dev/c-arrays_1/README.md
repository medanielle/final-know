```c
1 | int inputBuffer [256] = {0};
2 | 
```

## What is occuring in the C program snippet above?

KSAs: 263, 1338

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| Zero is placed only in the first element of the array. | ***Zero is placed in all elements of the array.*** | null is being placed in all elements of the array. | Number 0 through 255 are being placed in the array. |


Feedback:

- A) Incorrect: to place a zero in just first element would be done after the array is declared on the next line:  inputBuffer[0] = 0;
- B) Correct: Using the curly braces allows you to initialize an array when it is declared. In this case it initialize the first element to 0, but will also by default initialize all the remaining elements to zero
- C) Incorrect: you cannot initialize an integer to null
- D) Incorrect: the numbers are all set to zero, they do not authomatically increment for each element

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

