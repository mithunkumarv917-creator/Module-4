## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
dict1 = {
    "name": "Alice",
    "age": 20,
    "city": "New York"
}

dict2 = {
    "age": 25,
    "country": "USA",
    "profession": "Engineer"
}

def merge():
    merged_dict = {**dict1, **dict2}
    return merged_dict

print(merge())
```
## Output
<img width="862" height="74" alt="image" src="https://github.com/user-attachments/assets/b6422b70-cff7-4974-9e72-ccf3eefb7479" />

## Result
Thus the program has been executed successfully.
