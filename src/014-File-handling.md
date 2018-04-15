# Python file handling

### Opening a file
```python3
f = open(filename, mode)
f.close()  # where f is a file pointer
```

### File operations

|MODES|	DESCRIPTION|
|---|---|
|"r" |	 Open a file for read only|
|"w" |	 Open a file for writing. If file already exists its data will be cleared before opening. Otherwise new file will be created|
|"a" |	 Opens a file in append mode i.e to write a data to the end of the file|
|"wb" |	 Open a file to write in binary mode|
|"rb" |	 Open a file to read in binary mode|

### Writing data to the file
```python3
>>> f = open('myfile.txt', 'w')    # open file for writing
>>> f.write('this first line\n')   # write a line to the file
>>> f.write('this second line\n')  # write one more line to the file
>>> f.close()
```

### Reading data from a file
```python3
>>> f = open('myfile.txt', 'r')
>>> f.read() # read entire content of file at once
"this first line\nthis second line\n"
>>> f.close()
```

```python3
>>> f = open('myfile.txt', 'r')
>>> f.readlines() # read entire content of file at once
["this first line\n", "this second line\n"]
>>> f.close()
```

```python3
>>> f = open('myfile.txt', 'r')
>>> f.readline() # read entire content of file at once
"this first line\n"
>>> f.close()
```

### Appending data
```python3
>>> f = open('myfile.txt', 'a')
>>> f.write("this is third line\n")
19
>>> f.close()
```
