# Python Tuples

**Note**: Tuples are *immutable*.

### Creating a tuple
```python3
>>> t1 = () # creates an empty tuple with no data

>>> t2 = (11,22,33)

>>> t3 = tuple([1,2,3,4,4]) # tuple from array

>>> t4 = tuple("abc") # tuple from string
```


### Tuples functions
```python3
>>> t1 = (1, 12, 55, 12, 81)
>>> min(t1)
1
>>> max(t1)
81
>>> sum(t1)
161
>>> len(t1)
5
```


### Iterating through tuples
```python3
>>> t = (11,22,33,44,55)
>>> for i in t:
... print(i, end=" ")
>>> 11 22 33 44 55
```


### Slicing tuples
```python3
>>> t = (11,22,33,44,55)
>>> t[0:2]
(11,22)
```


### Operations
```python3
>>> t = (11,22,33,44,55)
>>> 22 in t
True
>>> 22 not in t
False

```
