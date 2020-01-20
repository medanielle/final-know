## In Python, given a list called myList, which places data into the current last element of the list?

KSAs: 32

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| myList(end) = 5 | myList[myList.end] = 5 | ***myList[len(myList)-1] = 5*** | len(myList) = 5 |


Feedback:

- A) Incorrect: This tries to assign 5 to a function call of myList(end), where end is a variable passed into the function; this is invalid syntax.
- B) Incorrect: This tries to assign 5 to the myList.end'th element; however, end is not a valid list attribute.
- C) Correct: This calculates the index of the last element and sets 5 to be the value of said element.
- D) Incorrect: This tries to assign 5 to the function call len(myList), which is invalid syntax.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

