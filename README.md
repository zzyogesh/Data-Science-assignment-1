# UpFlairs Summer Training - Basic Python (Assignment 1)

**Student Name:** Hemant
**Institution:** B.K. Birla Institute of Engineering & Technology, Pilani

---

### 1. Explain the difference between the following data types with examples:
* **Integer (`int`):** Represents whole numbers without a fractional or decimal component. They can be positive, negative, or zero.
  * *Example:* `x = 25`, `y = -10`
* **Float (`float`):** Represents real numbers with a decimal point. Used for precise measurements or fractional values.
  * *Example:* `pi = 3.14159`, `temperature = 98.6`
* **String (`str`):** A sequence of characters enclosed in single, double, or triple quotes. Used for text data.
  * *Example:* `name = "Hemant"`, `college = 'BKBIET'`
* **Boolean (`bool`):** Represents one of two values: `True` or `False`. Often used in conditional statements and logical operations.
  * *Example:* `is_student = True`, `is_graduated = False`

---

### 2. Write a Python program to create three variables (name, age, city) and print the values:
```python
# Creating variables with personal details
name = "Hemant"
age = 20
city = "Pilani"

# Printing the values in the requested format
print(f"Name: {name}")
print(f"Age: {age}")
print(f"City: {city}")

---
### 3. Write a Python program that takes input, prints uppercase, and prints character count:
# Taking user input
user_name = input("Enter your name: ")

# Printing in uppercase
print(f"Uppercase Name: {user_name.upper()}")

# Printing total number of characters
print(f"Total characters: {len(user_name)}")
