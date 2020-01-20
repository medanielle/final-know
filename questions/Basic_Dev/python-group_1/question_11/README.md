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

## What value does the getAverage function return?

KSAs: 24, 59, 80

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***12*** | 6 | 14 | 2 |


Feedback:

- Looking at line 8, the average of total/count is calculated and lines 4 - 6 sum up the total value and count number of people. Therefore, 16 + 7 + 15 + 2 + 20 = 60 and 60 / 5 people = 12.

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

