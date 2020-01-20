```python
1 | People = [
2 |     ["George","Jones"],
3 |     ["Bill","Johnson"],
4 |     ["Hank","Aaron"]
5 | ]
6 | 
```

## Given the above Python code snippet, how would you print out the word:  Aaron?

KSAs: 32

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| print(people[2]["Hank"]) | print(people[3][2]) | print(people[2,1]) | ***print(people[2][1])*** |


Feedback:

- A) Incorrect: people[2]["Hank"] is invalid syntax because list indices must be integers, not string.
- B) Incorrect: people[3][2] tries to access the third item, index 2, in a fourth nested list, index 3; however, both do not exist and are out of range. Remember, the index always starts at 0.
- C) Incorrect: people[2,1] tries to use a tuple of (2,1) to access a list item but this is invalid syntax because list indices must be integers.
- D) Correct: people[2][1] accesses the second item, index 1, in the third nested list, index 2.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

