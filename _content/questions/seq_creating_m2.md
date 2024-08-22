What will be the result of the following Python code?

```python
x = (1, 2, 3)
y = [4, 5, 6]
z = y * 2
result = x + tuple(z)
print(result)
```

**Options:**

A. `(1, 2, 3, 4, 5, 6, 4, 5, 6)`  
B. `(1, 2, 3) + [4, 5, 6, 4, 5, 6]`  
C. `(1, 2, 3, [4, 5, 6, 4, 5, 6])`  
D. `(1, 2, 3) + (4, 5, 6, 4, 5, 6)`

<!--
**Answer:** A

**Explanation:**
In the code, `x` is a tuple and `y` is a list. `z` is created by repeating `y` twice, resulting in `[4, 5, 6, 4, 5, 6]`. The `tuple(z)` converts this list into a tuple `(4, 5, 6, 4, 5, 6)`. Concatenating `x` and `tuple(z)` results in `(1, 2, 3, 4, 5, 6, 4, 5, 6)`.
-->