Given the following NumPy array:

```python
import numpy as np
array = np.array([[10, 20, 30], [40, 50, 60], [70, 80, 90]])
```

Which of the following code snippets correctly computes the variance of the sum of each row?

A) 
```python
variance_sum_rows = np.var(np.sum(array, axis=1))
```

B) 
```python
variance_sum_rows = np.var(array.sum(axis=1))
```

C) 
```python
variance_sum_rows = np.sum(np.var(array, axis=1))
```

D) 
```python
variance_sum_rows = np.var(array.sum(axis=0))
```

<!-- Answer: B) -->