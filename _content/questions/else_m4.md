You are writing a Python program to categorize the age of a person into different life stages with the following criteria:

- "Child" if the age is less than 13
- "Teenager" if the age is between 13 and 19 (inclusive)
- "Adult" if the age is between 20 and 64 (inclusive)
- "Senior" if the age is 65 or older

Which of the following code snippets correctly implements this classification using `if-elif-else`?

A) 
```python
age = 30

if age < 13:
    print("Child")
elif age <= 19:
    print("Teenager")
elif age <= 64:
    print("Adult")
else:
    print("Senior")
```

B) 
```python
age = 30

if age < 13:
    print("Child")
elif age <= 19:
    print("Teenager")
elif age < 65:
    print("Adult")
else:
    print("Senior")
```

C) 
```python
age = 30

if age < 13:
    print("Child")
elif age < 20:
    print("Teenager")
elif age < 65:
    print("Adult")
else:
    print("Senior")
```

D) 
```python
age = 30

if age < 13:
    print("Child")
else:
    if age <= 19:
        print("Teenager")
    elif age <= 64:
        print("Adult")
    else:
        print("Senior")
```

<!-- Answer: A) -->