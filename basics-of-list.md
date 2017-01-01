---
layout: page
title:  Basics of List
date:   2016-12-29 16:00:00 -0800
categories: curriculum
---

#### Explore - Definitions & Indexing

```python
l = [4, 2, 34, 9]
print( l[0])
print( l[1])
print( l[2])
print( l[3])
print( l[4]) # Gives an error
print( l[-1])
print( l[-2])
print( l[-3])
print( l[-4])
print( l[-5]) # Gives an error
```

```python
# Lists can take anything as value.
l = ['hello', 4, '324', 94]
print( l)
```



#### Practise

```python
l = [43, 3, 67, 98, 34]
print( l[___]) # fill in the blank so that it prints 67. Use positive & negative indexing.
print( l[___]) # fill in the blank so that it prints 34. Use positive & negative indexing.
print( l[___]) # fill in the blank so that it prints 43. Use positive & negative indexing.
```



#### Explore - Modifying a list

```python
l = [4, 42, 39, 12, 49]
l[ 1] = 33
print( l)

l[3] = 66
print( l)
```

```python
l = [4, 2]
l.append( 3)
print( l)

l.append( 9)
print( l)
```

```python
l = [43, 9, 10, 13, 44]

l.pop()
print( l)

l.pop( 2)
print( l)

del( l[1])
print( l)
```



#### Practise

```python
l = [44, 9, 23, 41, 84]

# What operation would convert this list into [44, 9, 32, 41, 84]?
# What operation would convert this list into [44, 9, 23, 41, 84, 14]?
# What operation would convert this list into [44, 9, 23, 41]?
# What operation would convert this list into [44, 23, 41, 84]?
```



#### Explore - Slicing

```python
l = [44, 9, 23, 41, 84, 74, 27, 64, 92]

print( l[ 1:3])
print( l[ 4:])
print( l[ :4])
print( l[ 1:-2])
```



#### Practise

```python
l = [44, 9, 23, 41, 84, 74, 27, 64, 92]

# What would give you the slice: [44, 9, 23, 41, 84, 74]?
# What would give you the slice: [23]?
# What would give you the slice: [64, 92]?
```



