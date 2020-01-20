```nasm
1 | mov rax, 1
2 | shl rax, 1
3 | shl rax, 3
4 | 
```

## In the above Assembly code, what's contained in the rax register when finished?

KSAs: 574, 576, 578, 579, 580, 596, 655, 1166, 1167, 1172

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***16*** | 8 | 1 | 2 |


Feedback:

- Correct: mov rax, 1 establihes 00000001 in the registry, shl (shift left) 1 modifies to: 00000010 (now 2), shl 3 modifies to: 00010000 (now 16)

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

