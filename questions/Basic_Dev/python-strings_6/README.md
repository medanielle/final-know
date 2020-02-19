```python
1 | str = 'pdf csv json'
2 | print(str.split())
3 | 
```

## What is the output for the above Python code snippet?

KSAs: 32, 42

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***['pdf', 'csv', 'json']*** | [pdf, csv, json] | pdf, csv, json | pdf csv json |


Feedback:

- Since nothing was passed into split(), the default delimiter, which is a space character, is used to split str into a list of sub-strings. When printed, the sub-string objects can be seen by the single quotes; without them, they would not be strings.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

