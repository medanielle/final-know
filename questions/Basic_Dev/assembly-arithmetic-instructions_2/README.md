## Which register in Assembly is the default register used for a counter?

KSAs: 574, 576, 596, 655, 1166, 1172

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| rax | ***rcx*** | rdx | rdi |


Feedback:

- A) Incorrect: rax is where values are returned from functions
- B) Correct: rcx is the default counter register
- C) Incorrect: rdx can be freely used but is not the default counter
- D) Incorrect: rdi is used in 64-bit Linux as function argument #1 and in 64-bit Windows it's preserved

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

