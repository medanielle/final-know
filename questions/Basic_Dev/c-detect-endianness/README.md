```c
1 | unsigned int x = 0xabcd1234;
2 | char *c = (char*) &x;
3 | printf("%x", *c)
4 | 
```

## In the above C code snippet, what is printed assuming the machine is big endian?

KSAs: 267

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***ab*** | cd | 12 | 34 |


Feedback:

- A) Correct: ab is stored first in big endian format
- B) Incorrect: cd is not stored first in either big or little endian format
- C) Incorrect: 12 is not stored first in either big or little endian format
- D) Incorrect: 34 would be printed if the machine is little endian

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

