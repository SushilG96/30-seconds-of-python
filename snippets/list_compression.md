---
title: power_of_two
tags: list compression,intermediate
---

List compression to simplifiy the code in single line
- Use `list compression` to simplify the code in a single line
- Return a list containing the resultant i.e square of each number in the list.
```py
def power_of_two(nums):
  return [x**2 for x in nums]
```

```py
power_of_two(2, 3, 5) # [4, 9, 25]
```
