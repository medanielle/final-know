```nasm
1  | .label1:
2  |     xor rax, rax
3  |     inc rax
4  |     mov rcx, rax
5  |     jmp .label2
6  |     mov rsp, rax
7  | .label2:
8  |     shl rcx, 3
9  |     xchg rcx, rax
10 |     ret
11 | 
```

## In the above Assembly code, which of the following is true?

KSAs: 574, 576, 578, 579, 580, 654, 661, 1166, 1167, 1172

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***The line mov rsp, rax is never executed*** | label1 and label2 are incorrectly defined | shl cannot be executed on the rcx register | jmp can only be used for label1 |


Feedback:

- A) Correct: this line is never executed because it is preceded by a jmp command with will always jump to the label2 when executed
- B) Incorrect: both these labels are correctly defined
- C) Incorrect: shl can be executed on the rcx register
- D) Incorrect: the jmp opcode can be used for any label

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

