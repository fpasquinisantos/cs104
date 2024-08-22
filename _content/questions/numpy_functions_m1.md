Given the following NumPy array:

```python
import numpy as np
array = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Which of the following code snippets correctly computes the sum of the maximum values in each column?

A) 
```python
sum_max = np.sum(np.max(array, axis=0))
```

B) 
```python
sum_max = np.max(np.sum(array, axis=0))
```

C) 
```python
sum_max = np.max(array, axis=1).sum()
```

D) 
```python
sum_max = np.sum(array)
```

<!-- Answer: A) -->