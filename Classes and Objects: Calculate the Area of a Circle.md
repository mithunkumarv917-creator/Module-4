# Classes and Objects in Python: Calculate the Area of a Circle

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
