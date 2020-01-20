## What is a difference between the yield keyword and the return keyword

KSAs: 92

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| yield temporarily blocks the program from executing | yield exits the program entirely | yield transfers interpreter control to the next thread in a threadpool | ***yield keeps function state after it returns a value*** |


Feedback:

- yield allows a generator function to keep its internal state after returning a value so it can be called repeatedly to iterate over data

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

