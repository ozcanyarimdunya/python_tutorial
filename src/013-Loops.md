# Python loops
**NOTE** Python has only two loops: *for* loop  and *while* loop

### For loop
```python3
my_list = [1,2,3,4]

for i in my_list:
    print(i)
```

### range(a, b) Function
```python3
for i in range(1, 10):
    print(i)
```

### While loop
```python3
count = 0

while count < 10:
    print(count)
    count += 1
```

```python3
count = 0

while count < 10:
    count += 1
    if count == 5:
         break
    print("inside loop", count)

print("out of while loop")
```

```python3
count = 0

while count < 10:
    count += 1
    if count % 2 == 0:
           continue
    print(count)

Output:
1
3
5
7
9
```
