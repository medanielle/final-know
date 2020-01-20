## Which of the following commands calls the kernel in Assembly programming?

KSAs: 578, 579, 580, 662, 668, 1166, 1168, 1170

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| mov 0x80 | ***int 0x80*** | call 0x80 | sys_exit |


Feedback:

- A) Incorrect: the mov opcode is used to mov contents into a register
- B) Correct: the int opcode is used to call the kernel
- C) Incorrect: call is not a valid opcode
- D) Incorrect: sys_exit is not a valid opcode

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

