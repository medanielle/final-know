```nasm
1 | mov rax, 1
2 | mov rcx, 5
3 | and rax, rcx
4 | 
```

## In Assembly, given the above what will rax contain in binary?

KSAs: 574, 576, 578, 579, 580, 596, 655, 1166, 1167, 1172

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***00000001*** | 00000100 | 00000110 | 00000101 |


Feedback:

- Correct: mov rax, 1 puts ...00000001 in rax, mov rcx, 5 puts ...00000101 in rcx, and-ing rax with rcx results in 00000001

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

