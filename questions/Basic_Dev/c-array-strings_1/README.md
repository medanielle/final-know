```c
1 | char str1[5] = {'H', 'e', 'l', 'l', 'o'};
2 | char *str2 = "Hello";
3 | 
```

## What is the difference between str1 and str2 if they are used as arguments to the printf() function with a string format?

KSAs: 263, 350

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***str1 may display additional text*** | str1 will have commas in between the letters when passed as an argument to printf() | str1 will only print out the first letter, H | There is no difference between them |


Feedback:

- When assigning a string using double quotes the compiler adds a null terminator. str1 is assigned an array explicitly without a null terminator. When passed to printf() if the byte after the 'o' is not a null terminator it will continue printing text until a null terminator is found in memory or the program crashes.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

