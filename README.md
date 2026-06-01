## Developed by: Mithun Kumar V (212225040236 / 25012629)

# 1.Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```
import math

class cse:
    def __init__(self,r):
        self.r=r
    def mech(self):
        return math.pi*r*r

r = int(input("Enter radius of circle to calculate the area: "))
obj = cse(r)
print(f"The area of the circle with radius {r} is {obj.mech()}")
```
## Output
<img width="653" height="66" alt="image" src="https://github.com/user-attachments/assets/1e24d969-9c9b-4f89-b906-8b6e10a1d64d" />

## Result
Thus the program has been executed successfully.


## 2.Dictionary Operations in Python: Merging Two Dictionaries

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

# 3.🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

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

# 4.Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = list(range(5))

try:
    print(list1[5])
except:
    print("You're out of list range")
```
## Output
<img width="354" height="50" alt="image" src="https://github.com/user-attachments/assets/e7bae7c9-ddbe-4534-be0d-d2f5eb865547" />

## Result
Thus the program has been executed successfully.

# 5.File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
count = 0
with open('story.txt','r') as file:
    contents = file.readlines()

    for i in contents:
        if i[0]=='T':
            count+=1
    file.close()
print("No of lines starting with T is:",count)

```
### story.txt
```
Riya loved watching the stars every night.

One evening, she noticed a bright light moving across the sky.

Curious, she followed it to a nearby hill.

There she found a tiny glowing bird trapped in a bush.

The bird spoke and thanked her for helping.

It explained that it came from a magical world above the clouds.

As a reward, it gave Riya a shining feather.

The feather could light up whenever someone needed help.

Riya used it to guide lost travelers and help her neighbors.

Soon, everyone in the village admired her kindness.

Years later, Riya realized that the bird's greatest gift was not the feather, but the lesson that helping others brings true happiness.

```
## Output
<img width="809" height="62" alt="image" src="https://github.com/user-attachments/assets/d72712b6-cdd7-4249-a926-3cee7054dadd" />

## Result
Thus the program has been executed successfully
