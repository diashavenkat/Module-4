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
my_dict = {'apple': 'fruit', 'carrot': 'vegetable', 'banana': 'fruit', 'date': 'fruit'}

sorted_by_keys = dict(sorted(my_dict.items()))

sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

print("Original Dictionary:", my_dict)
print("Dictionary sorted by keys:", sorted_by_keys)
print("Dictionary sorted by values:", sorted_by_values)

## Sample Output
<img width="782" height="276" alt="image" src="https://github.com/user-attachments/assets/278a6c2e-fd74-4a32-9125-a2eaa8197996" />


## Result
The program successfully sorts a dictionary by keys and by values in alphabetical order.



