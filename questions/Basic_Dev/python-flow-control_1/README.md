## Given a Python list called ages, which is the proper way to iterate through each item in the list.

KSAs: 32

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| for int a in ages: | ***for a in ages:*** | for range(a) in ages: | for range(ages): |


Feedback:

- A) Incorrect: Since Python doesn't require type declarations for variables, the int is not necessary and is a syntax error.
- B) Correct: This is the proper way to iterate through each item in a list.
- C) Incorrect: range(a) is in a position where an identifier, i.e. variable, is expected; you cannot assign the item's value to a function call.
- D) Incorrect: The loop has no identifier, i.e. variable, to use for each item in range(ages).

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

