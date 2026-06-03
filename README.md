# Assignment 1: Conceptual Questions

### Q1. Explain the difference between the following data types with examples:
* **Integer (`int`)**: Represents whole numbers without a fractional part. They can be positive, negative, or zero.
    * *Example:* `age = 20`
* **Float (`float`)**: Represents real numbers that contain a decimal point.
    * *Example:* `price = 99.99`
* **String (`str`)**: A sequence of characters enclosed in single, double, or triple quotes used to represent text.
    * *Example:* `city = "Pilani"`
* **Boolean (`bool`)**: Represents one of two built-in values: `True` or `False`. Used extensively in conditional logic.
    * *Example:* `is_passed = True`

---

### Q4. Explain any five commonly used string methods in Python with examples.

1.  **`upper()`**: Converts all characters in a string to uppercase.
    ```python
    text = "hello"
    print(text.upper())  # Output: 'HELLO'
    ```
2.  **`lower()`**: Converts all characters in a string to lowercase.
    ```python
    text = "WORLD"
    print(text.lower())  # Output: 'world'
    ```
3.  **`strip()`**: Removes any leading and trailing whitespaces from a string.
    ```python
    text = "  python  "
    print(text.strip())  # Output: 'python'
    ```
4.  **`replace(old, new)`**: Replaces a specified phrase with another specified phrase.
    ```python
    text = "I love Java"
    print(text.replace("Java", "Python"))  # Output: 'I love Python'
    ```
5.  **`split(separator)`**: Splits a string into a list where each word is a list item based on a delimiter.
    ```python
    text = "apple,banana,cherry"
    print(text.split(","))  # Output: ['apple', 'banana', 'cherry']
    ```

---

### Q7. What is Artificial Intelligence (AI)? Explain its importance and mention any four real-life applications of AI.

**Definition:** Artificial Intelligence (AI) refers to the simulation of human intelligence processes by machines, especially computer systems. These processes include learning (acquiring information and rules for using it), reasoning (using rules to reach approximate or definite conclusions), and self-correction.

**Importance:**
AI is critical because it enables automation of repetitive tasks, handles massive datasets to uncover hidden patterns, improves decision-making speed and accuracy, and solves complex real-world problems that are too large or intricate for manual human processing.

**Four Real-Life Applications:**
1.  **Healthcare:** Diagnostic tools using AI to detect tumors or anomalies in X-rays/MRIs.
2.  **E-commerce:** Recommendation engines (like Amazon) that predict what items you might want to buy next.
3.  **Autonomous Vehicles:** Self-driving cars (like Tesla) navigating traffic safely using computer vision.
4.  **Finance:** Fraud detection systems that monitor banking transactions in real-time to flag suspicious activity.

---

### Q8. Identify whether the following are examples of AI and explain why:

* **ChatGPT**: **Yes, it is AI.** It is a Large Language Model (LLM) based on Generative AI that processes and generates natural human-like text by predicting subsequent words based on patterns learned from data.
* **Google Maps route prediction**: **Yes, it is AI.** It utilizes machine learning algorithms, historic traffic data, and real-time user movement to predict optimal routes and accurately estimate arrival times.
* **Calculator**: **No, it is not AI.** It operates strictly on pre-defined, rigid mathematical rules and hardcoded programming. It cannot learn from previous computations, adapt to new contexts, or self-correct.
* **Netflix recommendations**: **Yes, it is AI.** It uses recommendation system algorithms (collaborative filtering and deep learning) to analyze user watch history and behavior to predict what content they will enjoy.
* **Voice assistants (Alexa/Siri)**: **Yes, it is AI.** They rely on Natural Language Processing (NLP) to interpret user speech, automatic speech recognition to transcribe it, and machine learning to execute the appropriate actions.# ==========================================



# Q2: Variable Creation and Printing
# ==========================================
print("--- Question 2 ---")
name = "Hemant"
age = 20
city = "Jaipur"

print(f"Name: {name}")
print(f"Age: {age}")
print(f"City: {city}")
print()

# ==========================================
# Q3: User Input and String Operations
# ==========================================
print("--- Question 3 ---")
user_name = input("Enter your name: ")
print(f"Uppercase Name: {user_name.upper()}")
print(f"Total number of characters: {len(user_name)}")
print()

# ==========================================
# Q5: Fruit List Operations
# ==========================================
print("--- Question 5 ---")
fruits = ["Apple", "Banana", "Mango", "Orange", "Cherry"]
print(f"Complete list: {fruits}")
print(f"First element: {fruits[0]} | Last element: {fruits[-1]}")
print(f"Total number of items: {len(fruits)}")
print()

# ==========================================
# Q6: Numeric List Manipulations
# ==========================================
print("--- Question 6 ---")
numbers = [10, 20, 30, 40, 50]
numbers.append(60)  # Add 60
numbers.remove(20)  # Remove 20
print(f"Updated list: {numbers}")
