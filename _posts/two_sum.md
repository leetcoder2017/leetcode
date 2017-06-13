---
layout: post
title:  Two Sum
---

| Time Complexity | Space Complexity |
|:----------------|:-----------------|
| O(n)            | O(n)             |

```python
visited = {}
for i, n in enumerate(nums):
        if target-n in visited:
                return [visited[target-n], i]
        else:
                visited[n]=i
        return []
```

Comment:
To create a solution of time complexity O(n), use a dictionary ```visited```.

Don't try hard to find a solution of Time O(n), Space O(1).
