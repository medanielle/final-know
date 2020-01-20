```c
1 | struct person {
2 |   char *name;
3 |   int age;
4 | } artist;
5 | 
```

## Given the above C code snippet, how would you initialize name in the struct person?

KSAs: 262, 346, 350

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| name.artist = "Picaso"; | person.name = "Picaso"; | artist->name = "Picaso"; | ***artist.name = "Picaso";*** |


Feedback:

- Line 4 declares a variable artist of type struct person simultaneously when the struct is defined. Accessing individual elements within a struct variable is done by using the . operator: artist.name, artist.age etc.  If artist were declared as a pointer, then accessing each element would use the -> operator such as:  artist->name, artist->age.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

