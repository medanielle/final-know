```nasm
1 | movzx rax, cl
2 | 
```

## In the above Assembly code, what's contained in the leftmost byte of the rax register?

KSAs: 574, 576, 578, 579, 580, 596, 598, 599, 600, 655, 1166, 1167, 1172

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| a copy of the cl contents | residual data | ***all zeroes*** | address of cl |


Feedback:

- A) Incorrect: Moving a smaller register (c1) to a larger register (rax) will result in the cl contents being placed in the rightmost bits
- B) Incorrect: The movzs puts all zeros in unfilled bits therefore there will be no residual data
- C) Correct: The movzx puts zeros in all unfilled bits from a mov command, because cl only has 8 bits, the leftmost 56 bits (7 bytes) are filled with zeros
- D) Incorrect: this mov command moves contents of a register not an address

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

