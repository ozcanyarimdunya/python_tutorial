# Python Strings
```python3
name = "Ozcan" | """Ozcan""" | 'Ozcan' | '''Ozcan'''
```

### Operations on string
```python3
name[0] = 'O'
```

```python3
name[1:3] = 'zc'
```

### Comparison
```python3
>>> "tim" == "tie"
False
>>> "free" != "freedom"
True
>>> "arrow" > "aron"
True
>>> "right" >= "left"
True
>>> "teeth" < "tee"
False
>>> "yellow" <= "fellow"
False
>>> "abc" > ""
True
>>>
```

### Iteration
```python3
>>> s = "hello"
>>> for i in s:
... print(i)
h
e
l
l
o
```

### Testing the string
```python3
>>> s = "welcome to python"
>>> s.isalnum()
False
>>> "Welcome".isalpha()
True
>>> "2012".isdigit()
True
>>> "first Number".isidentifier()
False
>>> s.islower()
True
>>> "WELCOME".isupper()
True
>>> "  \t".isspace()
True
```

### Converting the strings
```python3
s = "string in python"
>>> s1 = s.capitalize()
>>> s1
'String in python'
>>> s2 = s.title()
>>> s2
'String In Python'
>>> s = "This Is Test"
>>> s3 = s.lower()
>>> s3
'this is test'
>>> s4 = s.upper()
>>> s4
'THIS IS TEST'
>>> s5 = s.swapcase()
>>> s5
'tHIS iS tEST'
>>> s6 = s.replace("Is", "Was")
>>> s6
'This Was Test'
>>> s
'This Is Test'
>>>
```




