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

## What type of container is castNames?

KSAs: 31, 32, 33

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| List | ***Set*** | Dictionary | Tuple |


Feedback:

- A) Incorrect: A list is declared as [item_1, ... item_n]
- B) Correct: Since castNames is declared as {'Arya'}
- C) Incorrect: A dictionary is declared as {key_1:value_1, ... key_n:value_n}
- D) Incorrect: A tuple is declared as (item_1, ... item_n)

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

