# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d = {'banana': 3, 'apple': 1, 'cherry': 2}

sorted_keys = dict(sorted(d.items()))

sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))

print("Original Dictionary:", d)
print("Sorted by Keys:", sorted_keys)
print("Sorted by Values:", sorted_values)
```
## Sample Output
<img width="684" height="361" alt="image" src="https://github.com/user-attachments/assets/60092958-7250-40e7-9bd1-71ec3175178f" />

## Result
Thus, the Python program to sort a dictionary by keys and values was executed successfully, and the output obtained
