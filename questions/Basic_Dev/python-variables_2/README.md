```python
1 | x = 10
2 | x += 1
3 | 
```

## On the second line of the above Python snippet, x is now 11.  What else is occuring?

KSAs: 40, 38, 37

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| The original int object was changed from 10 to 11 because it's mutable. | ***A new int object is created because int objects are immutable*** | A new int object is created because int objects are static | The original int object was changed from 10 to 11 because it's dynamic. |


Feedback:

- Objects of built-in types like (int, float, bool, str, tuple, unicode) are immutable and Python int objects are not static unless they're declared as class variables.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

