## In Assembly, assume the rsi register contains the address of an array.  How do you access the data in the first element of the array?

KSAs: 574, 575, 576, 644, 1166, 1172

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| *rsi | rsi[0] | ***[rsi]*** | rsi->[0] |


Feedback:

- A) Incorrect: this is a C language pointer expression that accesses the first array element
- B) Incorrect: this is a C language array expression that accesses the first element
- C) Correct: this assembly instruction accesses the first value stored at the memory address in the rsi register
- D) Incorrect: this is not a valid assembly instruction

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

