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

import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        return area
try:
    radius_input = float(input("Enter the radius of the circle: "))
    circle = cse()
    area = circle.mech(radius_input)
    print(f"The area of the circle is: {area:.2f}")
except ValueError:
    print("Please enter a valid number for the radius.")
## Output
<img width="507" height="180" alt="image" src="https://github.com/user-attachments/assets/0071261b-a565-4404-8342-bd7bc6a9fdbf" />



## Result
The program successfully calculates the area of a circle using a Python class cse and its method mech. The user provides the radius, and the method computes and prints the area using the formula

