What will be the output of the following Python code?

```python
a = [1, 2, 3]
b = (4, 5, 6)
c = a + list(b)
print(c)
```

**Options:**

A. `[1, 2, 3, 4, 5, 6]`  
B. `[1, 2, 3, (4, 5, 6)]`  
C. `[1, 2, 3, 4, 5, 6, (4, 5, 6)]`  
D. `[1, 2, 3] + [4, 5, 6]`

<!--
**Answer:** A

**Explanation:** 
The code creates a list `a` and a tuple `b`. It then converts the tuple `b` to a list using `list(b)` and concatenates it with the list `a`. The result is a new list `[1, 2, 3, 4, 5, 6]`. The `+` operator combines the lists by appending the elements of `list(b)` to the end of `a`.
-->