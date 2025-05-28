# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
lis=[-10, 5] 
print(sum(lis)))
```

## Output

![439570789-ce370dbf-6797-41f2-94e8-ec94a8a04d98](https://github.com/user-attachments/assets/86d481e1-5b6c-4b64-8a83-be22cc820c23)

## Result

Thus the program to calculates the **sum of all elements** in a list is executed successfully.

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program

```
import re
lis=[] 
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items: 
   if not re.search(r"e",i): 
      lis.append(i) 
print(lis)
```
## Output

![439298870-f2d132bc-1988-4d51-957a-ca53442d39e9](https://github.com/user-attachments/assets/d96913e6-b885-4530-b3cd-dd9424015faf)

## Result

Thus the program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is executed successfully.

