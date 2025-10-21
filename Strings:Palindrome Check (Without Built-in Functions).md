# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
s = "google"


reversed_s = s[::-1]


if s == reversed_s:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```

## Output
<img width="1227" height="360" alt="image" src="https://github.com/user-attachments/assets/88c932db-bd98-45b7-88fb-e2152f8bba33" />


## Result
The program is executed.
