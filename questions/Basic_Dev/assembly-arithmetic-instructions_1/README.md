```nasm
1 | mov eax, 12
2 | mov ebx, 4
3 | add eax, ebx
4 | inc ebx
5 | inc eax
6 | shr eax, 1
7 | 
```

## In the above Assembly code, what does eax contain after all the operations?

KSAs: 573, 574, 576, 578, 579, 580, 597, 655, 1167, 1172

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| 17 | 16 | ***8*** | 18 |


Feedback:

- Line 1 moves the value 12 into the eax register and line 2 moves the value 4 into the ebx register. Line 3 adds the two values, storing the result (16) in the eax register. Line 4 can be ignored since the ebx register isn't used anymore. Line 5 increments the eax register value by one, now (17), and line 6 moves bit values right one spot, from 0001 0001 (17) to 0000 1000 (8).

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

