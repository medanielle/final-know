```python
1  | def getAverage(GoT):
2  |    tot = 0
3  |    count = 0
4  |    for rank in GoT.values():
5  |       tot += rank
6  |       count += 1
7  | 
8  |    return int(tot/count)
9  | 
10 | names = ['Cersei','Arya','Jon','Denerys','Tyrion','Jon','Sam','Arya'] 
11 |    
12 | peeps = {'Jon':16,'Denerys':7,'Tyrion':15,'Cersei':2,'Arya':20}
13 | 
14 | print(peeps[names[0]])
15 | 
16 | peeps['Tyrion'] = 18
17 | 
18 | avg = getAverage(peeps)
19 | 
20 | castNames = {'Arya'}
21 | 
22 | for name in names:
23 |    castNames.add(name)
24 | 
25 | print(names[len(names)])
26 | 
```

## What is the result of line 25 executing?

KSAs: 32, 43

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| Prints the string Arya | Prints Nothing | ***List index out of range error*** | Prints all strings in the list |


Feedback:

- Since the last index value of names is one minus its length, a list index out of range error occurs.

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

