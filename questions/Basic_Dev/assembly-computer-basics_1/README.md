```nasm
1 | mov rax, 0xc0ffee
2 | 
```

## The above Assembly code stores a memory address in the rax register.  Which instruction would store data at that address?

KSAs: 574, 576, 578, 579, 580, 596, 1166, 1167, 1172

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| mov rax, 100 | ***mov [rax], 100*** | add rax, 100 | mov 0xc0ffee, 100 |


Feedback:

- A) Incorrect: this instruction would replace the memory address in rax with the value 100
- B) Correct: to access the data for a given memory address, you use the [] brackets
- C) Incorrect: this command would simply modify the memory address
- D) Incorrect: the mov command needs to be followed by a valid operand (in this case a valid register name)

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

