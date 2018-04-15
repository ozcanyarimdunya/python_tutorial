# Python Exception Handling

### Simple
```python3
try:
    # write some code
    # that might throw exception
except <ExceptionType>:
    # Exception handler, alert the user
```


### Advanced
```python3
try:
    num1, num2 = eval(input("Enter two numbers, separated by a comma : "))
    result = num1 / num2
    print("Result is", result)

except ZeroDivisionError:
    print("Division by zero is error !!")

except SyntaxError:
    print("Comma is missing. Enter numbers separated by comma like this 1, 2")

except:
    print("Wrong input")

else:
    print("No exceptions")

finally:
    print("This will execute no matter what")
```


### raise Error
```python3
def enterage(age):
    if age < 0:
        raise ValueError("Only positive integers are allowed")

    if age % 2 == 0:
        print("age is even")
    else:
        print("age is odd")

try:
    num = int(input("Enter your age: "))
    enterage(num)

except ValueError as e:
    print("Only positive integers are allowed")
    print("Exception: ", e)
except:
    print("something is wrong")
```
