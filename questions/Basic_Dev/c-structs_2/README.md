```c
1  | struct Person {
2  |    char name[20];
3  |    int age;
4  | }p;
5  | 
6  | void main()
7  | {
8  |    struct Person * p=(struct Person p)malloc(sizeof(Person));
9  |    // Here...
10 | }
11 | 
```

## Given the above code, how would you assign a value to name in the Person struct object?

KSAs: 262, 346

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| Person->name = "Ted" | p.name = "Ted" | ***p->name = "Ted"*** | Person.name = "Ted" |


Feedback:

- On line 8, p is being declared as a poiinter of type struct Person. To access any element of a struct via a pointer, you use the pointer name followed by -> operator.  Therefor p->name to access the name, p->age to access the age.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

