Given the following 3D NumPy array:

```python
import numpy as np
array = np.array([[[3, 6, 9], [12, 15, 18]], 
                  [[21, 24, 27], [30, 33, 36]], 
                  [[39, 42, 45], [48, 51, 54]]])
```

Compute the maximum value for each 2D slice along the first axis and then calculate the mean of these maximum values. Describe your approach and provide the code you used to obtain this result.

<!--
To compute the maximum value for each 2D slice along the first axis and then find the mean of these maximum values:

1. **Extract Maximum Values:** Use `np.max` to find the maximum value for each 2D slice along the first axis.
2. **Calculate Mean:** Use `np.mean` to compute the mean of these maximum values.

**Code:**

```python
import numpy as np

array = np.array([[[3, 6, 9], [12, 15, 18]], 
                  [[21, 24, 27], [30, 33, 36]], 
                  [[39, 42, 45], [48, 51, 54]]])

# Find the maximum value for each 2D slice along the first axis
max_values = np.max(array, axis=(1, 2))

# Calculate the mean of these maximum values
mean_max_value = np.mean(max_values)

print(mean_max_value)
-->