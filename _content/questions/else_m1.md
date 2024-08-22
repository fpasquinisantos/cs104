You are analyzing temperature data in Python and want to classify each day as "Cold," "Moderate," or "Hot" based on the temperature. The classification criteria are:

- "Cold" if the temperature is below 10°C
- "Moderate" if the temperature is between 10°C and 25°C (inclusive)
- "Hot" if the temperature is above 25°C

Which of the following code snippets correctly implements this classification using `if-elif-else`?

A) 
```python
temperature = 20

if temperature < 10:
    print("Cold")
elif temperature <= 25:
    print("Moderate")
else:
    print("Hot")
```

B) 
```python
temperature = 20

if temperature < 10:
    print("Cold")
else if temperature <= 25:
    print("Moderate")
else:
    print("Hot")
```

C) 
```python
temperature = 20

if temperature < 10:
    print("Cold")
elif temperature < 25:
    print("Moderate")
else:
    print("Hot")
```

D) 
```python
temperature = 20

if temperature < 10:
    print("Cold")
else:
    print("Moderate")
elif temperature > 25:
    print("Hot")
```

<!-- Answer: A) -->