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
~~~
Name: SUBBIAH S
Reg No: 212223220111
~~~
```
input_dict = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}
sorted_items = sorted(input_dict.items())
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sorted_items:
    print(f"({key}, {value})", end=' ')
```

## Sample Output

![Screenshot 2025-04-28 230311](https://github.com/user-attachments/assets/30b7d09a-f409-4251-bfc8-f4ef06d1a920)
![Screenshot 2025-04-28 230324](https://github.com/user-attachments/assets/c71bf685-02b5-4ac5-b174-9b5b3f05cea0)

## Result

Thus the program executed successfully.
