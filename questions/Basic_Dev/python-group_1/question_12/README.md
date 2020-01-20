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

## What is occurring on line 16?

KSAs: 31

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***The value associated with 'Tyrion' is changed to 18*** | An additional key/value pair of 'Tyrion' and 18 is added | The value associated with 'Tyrion' is increased by 18 | None of the above |


Feedback:

- Since the dictionary 'peeps' already has a key of 'Tyrion', the value is changed to 18 because of the assignment operator. Duplicate keys aren't allowed in a dictionary object.

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

