# Introduction to Python

## 1. Python Basics

**What is Python, and why is it popular?**  
Python is a high-level, readable, and versatile programming language. 🌟  
- **Key Features**: Simple syntax, dynamic typing, large libraries, cross-platform.  
- **Use Cases**: Web development (Django, Flask), Data Science (pandas, NumPy), Automation, Machine Learning (TensorFlow). 🕸️📊🤖

![Popular Programming Languages](https://cdn.statcdn.com/Infographic/images/normal/16567.jpeg)

## 2. Installing Python

**Installation Steps:**

- **Windows**: 
  1. Download from [python.org](https://www.python.org/downloads/). 🖥️
  2. Run the installer, check "Add Python to PATH", and install. ✅
  3. Verify with `python --version`. 🔍

- **macOS**: 
  1. Download the installer from [python.org](https://www.python.org/downloads/). 🍎
  2. Run and follow the steps. ✅
  3. Verify with `python3 --version`. 🔍

- **Linux**: 
  1. `sudo apt update`. 🖥️
  2. `sudo apt install python3`. ✅
  3. Verify with `python3 --version`. 🔍

**Virtual Environment Setup:**
1. Install: `pip install virtualenv`. 
2. Create: `virtualenv venv`. 
3. Activate: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (macOS/Linux). 🌍

![Install Python](https://miro.medium.com/v2/resize:fit:640/format:webp/1*Z3UbzXmqa9zVgVI04uRwgg.gif)

## 3. Python Syntax and Semantics

**"Hello, World!" Program:**

```python
print("Hello, World!")

![Print Hello World](https://media.hackerearth.com/blog/wp-content/uploads/2016/10/python_print_hello.gif)

## 4. Data Types and Variables

**Basic Data Types:**

- int: Integer (e.g., 5) 🔢
- float: Decimal (e.g., 3.14) 💧
- str: String (e.g., "text") 📝
- bool: Boolean (True, False) ✔️❌

![Datatype Cheatsheet](https://qph.cf2.quoracdn.net/main-qimg-4129c7c9ff375c15d8b45504ca4b0208-lq)

## 5. Control Structures

- **Conditional Statement (if-else):**

  ![If-Else Execution](https://textbooks.cs.ksu.edu/intro-python/images/04/tutor7.gif?classes=border,shadow)

- **For Loop:**

  ![For loop Execution](https://bigl.es/content/images/2020/04/PYTHON-FOR-LOOP.gif)

## 6. Functions in Python

**Functions:**  
Functions are reusable code blocks. 🔄

- **Function Example:**

  ![Add Numbers](https://ineasysteps.com/wp-content/uploads/2023/02/arguments-in-python-function.png)

## 7. Lists and Dictionaries

**Lists vs. Dictionaries:**

- List: Ordered collection (e.g., [1, 2, 3]). 📋
- Dictionary: Key-value pairs (e.g., {'key': 'value'}). 🔑

- **Script Example:**

```
# List
  numbers = [1, 2, 3]
  for number in numbers:
      print(number)

# Dictionary
  person = {'name': 'Alice', 'age': 25}
  for key, value in person.items():
      print(f"{key}: {value}")

```

## 8. Exception Handling

**Handling Errors:**

'''
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Can't divide by zero!")
finally:
    print("Done")

```

## 9. Modules and Packages

**Modules & Packages:**

- Module: Python file (e.g., math). 📦
- Package: Collection of modules. 📁

**Using math Module**

```
import math
result = math.sqrt(16)
print(result)

```

## 10. File I/O

- **Read from File:**

![Read File}(https://i0.wp.com/www.101computing.net/wp/wp-content/uploads/Reading-Text-File-Animation-s.gif)

- **Write to File:**

```
lines = ["Hello, World!", "New line."]
with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')

```

## References

- [Python Official Documentation](https://docs.python.org/3/)
- [Python Installation Guide](https://docs.python.org/3/using/index.html)
- [Python Modules Documentation](https://docs.python.org/3/tutorial/modules.html)
- [Python File I/O Tutorial](https://www.w3schools.com/python/python_file_handling.asp)
