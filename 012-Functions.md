# Python Functions

### Creating functions
```python3
def function_name(arg1, arg2, arg3, .... argN):
     #statement inside function
```

### Simple
```python3
def sum(start, end):
   print(start, end)

   result = start + end
   print(result)

sum(10, 50)
```

### Function with return value.
```python3
def sum(start, end):
   result = start + end
   return result
s = sum(10, 50)
print(s)
```

### Argument with default values
```python3
def sum(start=10, end):
   result = start + end
   return result
s = sum(50)
```

### Keyword arguments
```python3
def sum(start=10, end):
   result = start + end
   return result
s = sum(end=50)
```


### Returning multiple values from Function
```python3
def sum(start=10, end):
   result = start + end
   return start, end, result
s, e, r = sum(end=50)
```

