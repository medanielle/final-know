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

## Which line contains a type cast?

KSAs: 25

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| 1 | ***8*** | 18 | 20 |


Feedback:

- A) Incorrect: This is a function declaration
- B) Correct: An integer cast is created using int()
- C) Incorrect: This calls the function getAverage(peeps) and assigns the return value to avg
- D) Incorrect: This creates a one item set with 'Arya' as the value and assigns it to castNames

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

