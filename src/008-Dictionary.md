# Python Dictionaries

### Creating Dictionary
```python3
friends = {
'tom' : '111-222-333',
'jerry' : '666-33-111'
}
```

### Retrieving, modifying and adding elements in the dictionary
```python3
>>> friends['tom']
'111-222-333'
```

```python3
>>> friends['bob'] = '888-999-666'
>>> friends
 {'tom': '111-222-333', 'bob': '888-999-666', 'jerry': '666-33-111'}
```

```python3
>>>  del friends['bob']
>>>  friends
{'tom': '111-222-333', 'jerry': '666-33-111'}
```

### Looping items in the dictionary
```python3
>>> friends = {
... 'tom' : '111-222-333',
... 'jerry' : '666-33-111'
...}
>>>
>>> for key in friends:
... print(key, ":", friends[key])
...
tom : 111-222-333
jerry : 666-33-111
>>>
>>>
```


### Operators
```python3
>>> 'tom' in friends
True
>>> 'tom' not in friends
False
```


### Dictionary methods
```python3
>>> friends = {'tom': '111-222-333', 'bob': '888-999-666', 'jerry': '666-33-111'}

>>> friends.popitem()
('tom', '111-222-333')

>>> friends.clear()

>>>  friends
{}

>>> friends = {'tom': '111-222-333', 'bob': '888-999-666', 'jerry': '666-33-111'}

>>> friends.keys()
dict_keys(['tom', 'bob', 'jerry'])

>>> friends.values()
dict_values(['111-222-333', '888-999-666', '666-33-111'])

>>> friends.get('tom')
'111-222-333'

>>> friends.get('mike', 'Not Exists')
'Not Exists'

>>> friends.pop('bob')
'888-999-666'

>>> friends
{'tom': '111-222-333', 'jerry': '666-33-111'}
```

