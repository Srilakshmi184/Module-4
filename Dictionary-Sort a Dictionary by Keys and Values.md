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
```c
data = {'banana': 'yellow', 'cherry': 'red', 'apple': 'green', 'blueberry': 'blue'}

sorted_by_keys = dict(sorted(data.items()))
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print("Original dictionary:", data)
print("Dictionary sorted by keys:", sorted_by_keys)
print("Dictionary sorted by values:", sorted_by_values)
```
## Sample Output
```c
Original dictionary: {'banana': 'yellow', 'cherry': 'red', 'apple': 'green', 'blueberry': 'blue'}
Dictionary sorted by keys: {'apple': 'green', 'banana': 'yellow', 'blueberry': 'blue', 'cherry': 'red'}
Dictionary sorted by values: {'blueberry': 'blue', 'apple': 'green', 'cherry': 'red', 'banana': 'yellow'}
```
## Result
The program successfully sorts the dictionary by its keys and values in alphabetical order and prints both sorted versions along with the original dictionary.
