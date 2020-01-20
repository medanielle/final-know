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

## On line 14, what is printed?

KSAs: 43, 45, 80

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***2*** | Jon | Cersei | 16 |


Feedback:

- Referring to lines 10 and 12, you can see that names[0] returns 'Cersei' and peeps['Cersei'] returns 2.

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

