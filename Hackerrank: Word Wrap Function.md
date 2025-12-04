# 🔄 Hackerrank : # 📦 Python Word Wrap Function

This Python program defines a function that **wraps a long string into multiple lines**, ensuring each line does not exceed a specified width.

---

## 🎯 Aim

To write a Python function that takes a long string and a specified width, and returns the string formatted with line breaks such that each line has **at most the given width**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Define a function `wrap(string, max_width)`:
   - Create an empty list `wrapped_lines` to store parts of the string.
   - Loop through the string using steps of `max_width`.
   - In each iteration, extract a substring of length `max_width`.
   - Append this substring to the list.
3. Join the list with `\n` to create the final string.
4. Return the result.
5. **End** the program.

---

Program
```python
def fun(s):

v,c=0,0

for i in s:

if i in ['A','E','I','O','U','a','e','i','o','u']:

    v+=1

else:

    c+=1
print("Number of Vowels:",v)

print("Number of Consonants:",c) s=input()
```
Sample Output
![491457768-1cf8ed22-3bed-410b-b6fa-ce3bcffe4b84](https://github.com/user-attachments/assets/8ab1b8ea-5c00-4e2b-95c3-196336cac40d)


## Result
Thus a python program to count the number of vowels and consonants from the given string  is excuted and verified.

