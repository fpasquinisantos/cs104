Given the following NumPy array:

```python
import numpy as np
array = np.array([[4, 8, 2], [10, 12, 6], [14, 16, 18]])
```

Which of the following code snippets correctly computes the sum of the mean values for each row?

A) 
```python
sum_mean = np.sum(np.mean(array, axis=1))
```

B) 
```python
sum_mean = np.mean(np.sum(array, axis=1))
```

C) 
```python
sum_mean = np.sum(array) / array.size
```

D) 
```python
sum_mean = np.mean(array, axis=0).sum()
```

<!-- Answer: A) -->