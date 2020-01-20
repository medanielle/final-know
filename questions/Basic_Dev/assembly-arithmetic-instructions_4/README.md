```nasm
1 | move rax, 5
2 | xor rax, rax
3 | 
```

## In the above Assembly code, what does rax contain after all the operations?

KSAs: 574, 576, 578, 579, 580, 596, 655, 1166, 1167, 1172

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| 5 | 10 | 1 | ***0*** |


Feedback:

- For XOR, if the bits from the operands are same (both 0 or both 1), the resultant bit is cleared to 0. Because both values have the same bits the resuts are all zeros

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

