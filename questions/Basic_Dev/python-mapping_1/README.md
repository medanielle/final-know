## Which of the following is a valid declaration of a dictionary in Python?

KSAs: 31, 45

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***dict={'Country':'India','Capital':'Delhi','PM':'Modi'}*** | dict=['Country':'India','Capital':'Delhi','PM':'Modi'] | dict={'Country'-'India','Capital'-'Delhi','PM'-'Modi'} | dict={'Country','India','Capital','Delhi','PM','Modi'} |


Feedback:

- A) Correct: The valid declaration of a Python dictionary object is dict = {}, for a blank dictionary or dict = {key:value, ... key_n:value_n}.
- B) Incorrect: This tries to use a list as a dictionary, since square brackets create list objects, and is invalid syntax.
- C) Incorrect: You must use a colon as the key:value separator, not dash; this is invalid syntax.
- D) Incorrect: This creates a set, not a dictionary.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

