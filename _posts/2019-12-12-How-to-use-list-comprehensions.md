---
layout: post
title:  "Welcome to Python Tutorial"
---

*List comprehensions* provide a concise way to create lists. Common applications are to make new lists where each element is the result of some operations applied to each member of another sequence or iterable, or to create a subsequence of those elements that satisfy a certain condition.

```python
# Method One normal
squares = []
for x in range(10):
    squares.append(x**2)

# >>> squares
# [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]

# Above code with more pythonic approach
squares = [x**2 for x in range(10)]
```