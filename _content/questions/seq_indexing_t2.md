What will be the output of the following Python code?

```python
matrix = [[7, 8, 9], [10, 11, 12]]
matrix[1][3] = 13
print(matrix)
```

<!--
**Explanation:**
The code attempts to assign the value `13` to `matrix[1][3]`, which refers to the fourth element of the second sublist in `matrix`. Since `matrix[1]` only has three elements, trying to access index `3` raises an `IndexError` because it is out of range.
-->