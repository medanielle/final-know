## In python when using inheritance how would you call the __init__() function of a parent class inside a subclass __init__() function

KSAs: 109, 110

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| ancestor.__init__() | ***super.__init__()*** | parent.__init__() | base.__init__() |


Feedback:

- the super keyword is used to reference an item in the inherited base class from the sub-class in python.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

