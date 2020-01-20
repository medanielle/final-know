## In Assembly, which of the following is the proper way to add 1 to the value stored in the rax register?

KSAs: 574, 579, 580, 596, 655, 1166, 1167, 1172

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| mov rax, rax+1 | rax++ | ***add rax, 1*** | add rax+1 |


Feedback:

- A) Incorrect: The + operator is not a valid opcode
- B) Incorrect: The ++ operator is not a valid opcode
- C) Correct: In assemby you use the add opcode, followed by the operand (in this case rax), followed by a comma and an amount to add
- D) Incorrect: The + operator is not a valid opcode

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

