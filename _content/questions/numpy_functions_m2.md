Given the following NumPy array:

```python
import numpy as np
array = np.array([[2, 4, 6], [8, 10, 12], [14, 16, 18]])
```

Which of the following code snippets will correctly compute the mean of the minimum values from each row?

A) 
```python
mean_min = np.mean(np.min(array, axis=1))
```

B) 
```python
mean_min = np.min(np.mean(array, axis=1))
```

C) 
```python
mean_min = np.mean(array)
```

D) 
```python
mean_min = np.min(array, axis=0).mean()
```

<!-- Answer: A) -->