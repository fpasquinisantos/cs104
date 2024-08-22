In a Python program, you need to classify the severity of a storm based on wind speed using the following categories:

- "Light" if the wind speed is less than 20 km/h
- "Moderate" if the wind speed is between 20 km/h and 50 km/h (inclusive)
- "Strong" if the wind speed is between 51 km/h and 100 km/h (inclusive)
- "Severe" if the wind speed is greater than 100 km/h

Which of the following code snippets correctly implements this classification using `if-elif-else`?

A) 
```python
wind_speed = 55

if wind_speed < 20:
    print("Light")
elif wind_speed <= 50:
    print("Moderate")
elif wind_speed <= 100:
    print("Strong")
else:
    print("Severe")
```

B) 
```python
wind_speed = 55

if wind_speed < 20:
    print("Light")
elif wind_speed <= 50:
    print("Moderate")
else if wind_speed <= 100:
    print("Strong")
else:
    print("Severe")
```

C) 
```python
wind_speed = 55

if wind_speed < 20:
    print("Light")
elif wind_speed <= 50:
    print("Moderate")
elif wind_speed < 100:
    print("Strong")
else:
    print("Severe")
```

D) 
```python
wind_speed = 55

if wind_speed < 20:
    print("Light")
else:
    if wind_speed <= 50:
        print("Moderate")
    elif wind_speed <= 100:
        print("Strong")
    else:
        print("Severe")
```

<!-- Answer: A) -->