---
layout: post
title:  Two Sum
date:   2015-11-15 19:02:34 +0800
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
