---
layout: page
title:  Conditionals
date:   2016-12-29 15:00:00 -0800
categories: curriculum
---

#### Explore - if-else Basics

```python
if 2 > 1:
    print "2 is grater than 1"
```

```python
# Try this code for different values of x & y.
# x = 1, y = 2
# x = 4, y = 4
# x = 14, y = 9
# x = "abc", y = "xyz"
# x = "c", y = "cde"
# x = "MNO", y = "DUV"
# x = "abcd", y = "abce"
# x = True, y = False

x = 1
y = 2

if x > y:
    print "x is greater than y"
elif x == y:
    print "x is equal to y"
else:
    print "x is less than y"
```

```python
x = 2
y = 1
z = 0

if x > y and y > z:
    print True
else:
    print False
```

```python
x = 2
y = 1
z = 3

if (x > y and y > z) or z > x:
    print True
else:
    print False
```



#### Practise

```python
# Fill in the blank so that this code prints True
x = 1
y = ___
if x > y:
	print True
```

```python
# Fill in the blank so that this code prints False
x = "abc"
y = ___
if x > y:
    print True
else:
    print False
```

```python
# Find the values of a, b, c, d and e so that this code prints 1
# Find the values of a, b, c, d and e so that this code prints 2
# Find the values of a, b, c, d and e so that this code prints 3
# Find the values of a, b, c, d and e so that this code prints 4
# Find the values of a, b, c, d and e so that this code prints 5
# Find the values of a, b, c, d and e so that this code prints 6

a = ___
b = ___
c = ___
d = ___
e = ___

if a > b:
    if b > c and d > e:
        print 1
    elif c > d:
        print 2
    else:
        print 3
elif c < d:
    if e > a:
        if c < a and c < e:
            print 4
        else:
            print 5
    else:
        print 6
```





