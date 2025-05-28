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

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program

```
def remove(a):
    for i in range(len(a)):
        if(i==x):
            pass
        else:
            print(a[i],end="")
x=int(input())

```

## Output

![image](https://github.com/user-attachments/assets/afa95fe7-0660-4d69-bd6d-d15dd1cce2be)

## Result

Thus the program to accepts a string and removes the character at a specified index is executed successfully.

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign a string to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```
a = input()
rev = a[::-1]
if a == rev:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output

![439303392-37a520cc-8193-4412-9175-8e9641a46eb6](https://github.com/user-attachments/assets/d7bed57c-e7c9-468d-8b77-0431768bfb30)

## Result

Thus the program to check whether the string is a **palindrome** or not, without using built-in palindrome checking functions is executed successfully.

