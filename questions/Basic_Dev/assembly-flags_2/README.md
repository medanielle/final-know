## In Assembly with a 32-bit architecture, what happens when an add or sub operation causes the 33rd bit to be modified?

KSAs: 573, 597, 580, 659, 1166

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***The Carry Flag is set*** | the rax register is set to 1 | the unsigned number becomes signed | a virtual 64-bit register is created |


Feedback:

- The Carry Flag (CF) is set when an arithmetic borrow or carry occurs during add/sub - e.g. the result of an add would have set bit 33 (in x86), or bit 65 (in x86_64)

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

