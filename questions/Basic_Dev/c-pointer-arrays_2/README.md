```c
1 | char * Text = "This is a test"; 
2 | Text += 2;
3 | 
```

## Given the above code, what is the output if *Text is printed?

KSAs: 255, 262

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| is is a test | ***i*** | an address | This is a test |


Feedback:

- A) Incorrect: if text were printed instead of *text, then this would be correct
- B) Correct: text is a character pointer and dereferencing text *text will print a single character
- C) Incorrect: *text is a dereference and will print content not an address
- D) Incorrect: First, the pointer has been advanced 2 chars past the beginning of the array, second *text is a dereference to a char and will only print a singe char

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

