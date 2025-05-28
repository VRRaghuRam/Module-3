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
