What will be the output of the following Python code?

```python
nested_list = [[1, 2], [3, 4]]
nested_list[0][2] = 5
print(nested_list)
```


<!--
**Explanation:**
The code attempts to assign the value `5` to `nested_list[0][2]`, which refers to the third element of the first sublist in `nested_list`. Since `nested_list[0]` only has two elements, trying to access index `2` raises an `IndexError` because it is out of range.
-->