## Which of the following is the proper way to access a value from a Python dictionary called car?

KSAs: 31

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| car.model | ***car["model"]*** | car{model} | car.model() |


Feedback:

- A) Incorrect: This accesses an attribute of a Python class.
- B) Correct: The name of the key is placed between square brackets, just like you would the index number to a list. Note, key names can't be hashable values, that is, values containing lists, dictionaries or other mutable types (that are compared by value rather than by object identity).
- C) Incorrect: The key of a Python dictionary is placed between square brackets not curly brackets.
- D) Incorrect: This accesses a class function.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

