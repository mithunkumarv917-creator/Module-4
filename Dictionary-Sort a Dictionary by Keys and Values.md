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
student_marks = {
    "Ravi": 85,
    "Anita": 92,
    "Karan": 78,
    "Priya": 88
}

sorted_by_keys = dict(sorted(student_marks.items()))

sorted_by_values = dict(sorted(student_marks.items(), key=lambda item: item[1]))

print("Original Dictionary:")
print(student_marks)

print("\nDictionary Sorted by Keys:")
print(sorted_by_keys)

print("\nDictionary Sorted by Values:")
print(sorted_by_values)


```
## Sample Output
<img width="661" height="247" alt="image" src="https://github.com/user-attachments/assets/5cc6945b-d0a7-42db-884a-b934343a82ea" />

## Result
Thus the program has been executed successfully.
