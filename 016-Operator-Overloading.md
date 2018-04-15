# Python Operator Overloading
```python3
import math

class Circle:

    def __init__(self, radius):
        self.__radius = radius

    def setRadius(self, radius):
        self.__radius = radius

    def getRadius(self):
        return self.__radius

    def area(self):
        return math.pi * self.__radius ** 2

    def __add__(self, another_circle):
        return Circle( self.__radius + another_circle.__radius )

c1 = Circle(4)
print(c1.getRadius())

c2 = Circle(5)
print(c2.getRadius())

c3 = c1 + c2 # This became possible because we have overloaded + operator by adding a    method named __add__
print(c3.getRadius())
```


### Operators

|OPERATOR	|FUNCTION	  |METHOD DESCRIPTION|
|---|---|---|
|+ 	 | __add__(self, other) 	| Addition|
|* 	 | __mul__(self, other) 	| Multiplication|
|- 	 | __sub__(self, other) 	| Subtraction|
|% 	 | __mod__(self, other) 	| Remainder|
|/ 	 | __truediv__(self, other) |	 Division|
|< 	 | __lt__(self, other) 	| Less than|
|<= 	 | __le__(self, other) 	| Less than or equal to|
|== 	 | __eq__(self, other) |	 Equal to|
|!= 	 | __ne__(self, other) |	 Not equal to|
|> 	 | __gt__(self, other) |	Greater than|
|>= 	 | __ge__(self, other) 	 |Greater than or equal to|
|[index] 	 | __getitem__(self, index) 	| Index operator|
|in 	 | __contains__(self, value) |	Check membership|
|len |	__len__(self) 	| The number of elements|
|str |	__str__(self) |	 The string representation|

### Sample
```python3
import math

class Circle:

    def __init__(self, radius):
        self.__radius = radius

    def setRadius(self, radius):
        self.__radius = radius

    def getRadius(self):
        return self.__radius

    def area(self):
        return math.pi * self.__radius ** 2

    def __add__(self, another_circle):
        return Circle( self.__radius + another_circle.__radius )

    def __gt__(self, another_circle):
        return self.__radius > another_circle.__radius

    def __lt__(self, another_circle):
        return self.__radius < another_circle.__radius

    def __str__(self):
        return "Circle with radius " + str(self.__radius)

c1 = Circle(4)
print(c1.getRadius())

c2 = Circle(5)
print(c2.getRadius())

c3 = c1 + c2
print(c3.getRadius())

print( c3 > c2) # Became possible because we have added __gt__ method

print( c1 < c2) # Became possible because we have added __lt__ method

print(c3) # Became possible because we have added __str__ method
```
