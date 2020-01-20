```nasm
1 | mov rdx, 0
2 | mov rax, 10
3 | mov rcx, 2
4 | div rcx
5 | 
```

## In the above Assembly code, what does rax contain after all the operations?

KSAs: 574, 576, 578, 579, 580, 596, 655, 1166, 1167, 1172

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 10 | 0 | ***5*** | 1 |


Feedback:

- div takes a single argument (value in rcx), and divides the value stored in the dividend register (rax) by it.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

