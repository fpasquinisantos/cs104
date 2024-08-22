Given the following NumPy array:

```python
import numpy as np
array = np.array([[10, 20, 30], [40, 50, 60], [70, 80, 90]])
```

What will be the result of the following code snippet?

```python
result = array[::2, 1:]
```

A) 
```python
array([[10, 20, 30],
       [70, 80, 90]])
```

B) 
```python
array([[10, 20],
       [70, 80]])
```

C) 
```python
array([[20, 30],
       [80, 90]])
```

D) 
```python
array([[20, 30],
       [50, 60]])
```

<!-- Answer: C) -->