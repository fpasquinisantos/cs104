What will be the output of the following Python code?

```python
grid = [[0, 1], [2, 3, 4]]
grid[0][3] = 5
print(grid)
```

<!--
**Explanation:**
The code attempts to assign the value `5` to `grid[0][3]`, which refers to the fourth element of the first sublist in `grid`. Since `grid[0]` only has two elements, trying to access index `3` raises an `IndexError` because it is out of range.
-->