```c
1 | char s[20] = "Hello\0Hi";
2 | 
3 | printf("%s", s);
4 | 
```

## What is the output of the above C code snippet?

KSAs: 350

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| Hello\\0Hi | Hello Hi | ***Hello*** | Hi |


Feedback:

- The printf's behavior when printing a char array is to print each character until the NULL (\0) character is encounterd.  Therefore, only 'Hello' will print. In c programming the \0 char signifies the end of a string.  If you did strlen(s) the result would be 5.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

