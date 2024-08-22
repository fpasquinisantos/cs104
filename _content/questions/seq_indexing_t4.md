What will be the output of the following Python code?

```python
coordinates = [[10, 20, 30], [40, 50]]
coordinates[1][2] = 60
print(coordinates)
```

<!--
**Explanation:**
The code attempts to assign the value `60` to `coordinates[1][2]`, which refers to the third element of the second sublist in `coordinates`. Since `coordinates[1]` only has two elements, trying to access index `2` raises an `IndexError` because it is out of range.
-->