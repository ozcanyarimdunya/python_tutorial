# Python Modules

Python module is a normal python file which can store function,
variable, classes, constants etc. Module helps us to organize
related codes . For e.g math module in python has mathematical
related functions.

### Creating module
Create a new file called **mymodule.py** and write the following code.

```python3
foo = 100

def hello():
    print("i am from mymodule.py")
```

In another file

```python3
import mymodule

print(mymodule.foo)
print(mymodule.hello())
```

```python3
Output:
100
i am from mymodule.py
```

### Extra
```python3
from mymodule import foo # this statement import only foo variable from mymodule
print(foo)
```

```python3
>>> dir(mymodule)
['__builtins__', '__cached__', '__doc__', '__file__',
'__loader__', '__name__', '__package__', '__spec__', 'foo', 'hello']
```
