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

## What type of container is names?

KSAs: 42, 43

## Answer
| ***A*** | B | C | D |
| :--- | :--- | :--- | :--- |
| ***List*** | Array | String | Set |


Feedback:

- A) Correct: A list is declared with square brackets.
- B) Incorrect: Python does not have array containers.
- C) Incorrect: A string is declared by surrounding text with either single or double quotes.
- D) Incorrect: A set is declared using curly brackets and comma separated values, no key-value pairs present.

[**<- Back To Basic Dev**](../../../../Basic_Dev.md)

