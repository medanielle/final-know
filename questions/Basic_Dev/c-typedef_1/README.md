```c
1 | typedef unsigned int counter;
2 | 
```

## What does this code do?

KSAs: 349

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| Creates an unsigned int named counter. | ***Creates a new type named counter that acts like an unsigned int.*** | Creates a variable named counter that has no type defined until runtime | Creates a new struct that can only hold unsigned int |


Feedback:

- A) Incorrect: typedef does not create variables, it creates a new type that acts like the type specified.
- B) Correct: typedef defines a type with another name to be used in specific contexts.
- C) Incorrect: C can not allocate memory on the stack at runtime. typedef creates a new type that acts like the type specified.
- D) Incorrect: typedef can be used to define structs but it is only defining a single unsigned int as counter.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

