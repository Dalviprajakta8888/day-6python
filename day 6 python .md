```python
# program in python to convert two lists into dictionary 
```


```python
list1=[1,2,3,4,5,7,8]
list2=["a","b","c","d",]
d={}
for i in range(len(list2)):
    list1.append(list2[i])
for i in list1:
    d[i]=i
print(d)    

```

    {1: 1, 2: 2, 3: 3, 4: 4, 5: 5, 7: 7, 8: 8, 'a': 'a', 'b': 'b', 'c': 'c', 'd': 'd'}
    


```python

```
