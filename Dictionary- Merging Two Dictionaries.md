## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4, 'e': 5}

def merge(d1, d2):
    return {**d1, **d2}

merged_dict = merge(dict1, dict2)
print("Merged Dictionary:", merged_dict)

## Output
<img width="664" height="124" alt="image" src="https://github.com/user-attachments/assets/9ecb6c87-b637-410a-9e15-2fcd508c94a0" />

## Result
The program successfully merges two dictionaries using the unpacking operator (**). Keys from dict2 overwrite duplicates from dict1, and the final dictionary combines all key-value pairs.

