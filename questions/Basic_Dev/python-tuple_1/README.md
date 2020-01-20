```python
1 | age_book = {"Sam" : 19, "Timmy" : 24, "Beth" : 22}
2 | 
3 | ages = get_ages(age_book)
4 | age_collection = [ages[0], ages[1], ages[2]]
5 | 
6 | def get_ages(a):
7 |     return a["Sam"], a["Timmy"], a["Beth"]
8 | 
```

## Which of the following is a Python tuple?

KSAs: 24, 29, 31, 32, 33

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| age_book | ***ages*** | age_collection | Both ages and age_collection |


Feedback:

- A) Incorrect: This is a dictionary
- B) Correct: get_ages returns a tuple containing all of the return values
- C) Incorrect: This is a list
- D) Incorrect: ages is a tuple but age_collection is a list

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

