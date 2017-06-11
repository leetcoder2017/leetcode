```python
visited = {}
for i, n in enumerate(nums):
        if target-n in visited:
                return [visited[target-n], i]
        else:
                visited[n]=i
        return []
```
