```nasm
1 | mov rax, 2
2 | shr rax, 2
3 | shl rax, 2
4 | 
```

## In the above Assembly code, what's contained in the rax register when finished?

KSAs: 574, 576, 578, 579, 580, 596, 655, 1166, 1167, 1172

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 2 | 1 | ***0*** | 4 |


Feedback:

- mov rax, 2 puts ...00000010 into rax, shr (shift right) 2, shifts bits 2 to right resulting in ...00000000 in rax, shl (shift left) 1 shifts all bits one to left but has no affect because register is all zeros

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

