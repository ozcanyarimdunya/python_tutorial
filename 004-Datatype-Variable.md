# Datatype & Variables
### Expect all this you can define your python variable as you want
```python
False      class      finally    is         return
None       continue   for        lambda     try
True       def        from       nonlocal   while
and        del        global     not        with
as         elif       if         or         yield
pass       else       import     assert
break      except     in         raise
```

### Variable declaration
```python3
x = 100                       # x is integer
pi = 3.14                     # pi is float
empname = "python is great"   # empname is string

a = b = c = 100 # this statement assign 100 to c, b and a.
```

### Simultaneous Assignments
```python3
Python

var1, var2, varn = exp1, exp2, expn
a, b, c = 4, 3, 2
```

### Python data types
Python has 6 standard data types namely.

1. Numbers
2. String
3. List
4. Tuple
5. Dictionary
6. (Exceptional)Boolean

**NOTE** In Python True and False  are boolean literals.
But the following values are also considered as false.
- 0, 0.0 ,
- [], (), {}, ''
- None

### Receiving input from Console
*input()*  function is used to receive input from the console.

Syntax:  input('any prompt') -> string

```python3
>>> name = input("Enter your name: ")
>>> Enter your name: ozcan
>>> name
'ozcan'
```
```python3
>> age = int(input("Enter your age: "))
Enter your age: 24
>>> age
24
>>> type(age)
<class 'int'>
```


