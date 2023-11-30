## What will variable(x) contain?

```python
x = str(3)
```

%

'3'

## What will variable(y) contain?

```python
y = int(3)
```

%

3

## What will variable(z) contain?

```python
x = float(3)
```

%

3.0

## What does ... do?

```python
type()
```

%

Takes in a variable as a param and returns its data type. For example:

```python
x = 7.0
print(type(x)) # 'float'
```

## Will variable(A) overwrite variable(a), why or why not?

```python
a = 4
A = 'Becky'
```

%

variables are case-sensitive in python

## Is the following variable name valid?

```python
    2myvar = 'Mack'
```

%

No. Variable names cannot start with a number

## Is the following variable name valid?

```python
    my-var = 'Mack'
```

%

No. Variable names must only include alphanumeric chars and underscores

## Is the following variable name valid?

```python
    _my_var = 'Mack'
```

%

Yes. Variable name only includes alphanumeric chars and underscores

## How can I assign the values "Orange", "Banana" & "Cherry" to the variables x, y, z in a single line

```python
    x, y, z = "Orange", "Banana", "Cherry"
```

## How can I assign the value "Orange"to the variables x, y, z in a single line

```python
    x = y = z = 'Orange'
```

## What is the output of the following piece of code?

```python
super_heros = ['superman', 'batman', 'spiderman']
x , y, z = super_heros

print(x)
print(y)
print(z)
```

%

superman
batman
spiderman

collection of values in list, tuple can be extracted into variable, called unpacking

## What is the output of the following piece of code?

```python
super_heros = ['superman', 'batman', 'spiderman']
x , y, z = super_heros

print(x,y,z)
```

%

superman batman spiderman

## What is the output of the following piece of code?

```python
me = ['I ', 'am ', 'cool']
x , y, z = me

print(x + y + z)
```

%

I am cool

## What is the output of the following piece of code?

```python
me = ['I', 'am', 'cool']
x , y, z = me

print(x + y + z)
```

%

Iamcool

## What is the output of the following piece of code?

```python
x = 6
y = "mack"

print(x + y)
```

%

TypeError: unsupported operand type(s) for +: 'int' and 'str'

## What is the output of the following piece of code?

```python
x = 6
y = "mack"

print(x, y)
```

%

6 mack
