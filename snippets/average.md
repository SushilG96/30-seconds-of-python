---
title: average
tags: math,list,beginner
---

Returns the average of two or more numbers.

- Use `sum()` to sum all of the `args` provided, divide by `len(args)`.

```py
def average(*args):
  return sum(args, 0.0) / len(args)
```

```py
average(*[1, 2, 3]) # 2.0
average(1, 2, 3) # 2.0
```
