```python
1 | myList = ["Jim", "Bob", "Matt", "Tom"]
2 | 
```

## Which Python string function would you use to combine a list of strings into one string with each word separated by a space?

KSAs: 42, 43

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| " ".append(myList) | myList.append(" ") | ***" ".join(myList)*** | " ".collect(myList) |


Feedback:

- A) Incorrect: This will attempt to append myList to the end of the space character; however, append() is not a valid string function.
- B) Incorrect: This will append a space character to the end of myList.
- C) Correct: This will use the space character to join the items in myList. Note, if myList has non-string types then the join operation will most likely cause an error.
- D) Incorrect: This will attempt to use an invalid collect() string function.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

