```nasm
1 | mov rax, 1
2 | mov rcx, 5
3 | 
4 | or rax, rcx
5 | 
```

## In the above Assembly code, what's contained in the rax register when finished?

KSAs: 574, 576, 578, 579, 580, 596, 655, 1166, 1167, 1172

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 1 | ***5*** | 6 | 0 |


Feedback:

- Correct: mov rax, 1 puts ...00000001 in rax, mov rcx, 5 puts ...00000101 in rcx, or-ing rax with rcx results in 00000101

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

