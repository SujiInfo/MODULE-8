# PYTHON PROGRAMMMINDG MODULE 8

### NAME : SANGAMITHRA B
### REGISTER NUMBER : 212224060035

# # Hackerrank:# Student Topper Finder

This Python program helps determine the **top-performing student** based on the total marks across five subjects. It uses a dictionary to store each student’s marks and identifies the topper using simple calculations and built-in functions.

---

##  Aim

To maintain a dictionary of students with their marks in five subjects, calculate their **total marks**, store them in a new dictionary, and identify the **student with the highest total (topper)**.

---

##  Algorithm

1. **Start** the program.
2. Create a dictionary `student_marks`:
   - Keys → Student names.
   - Values → List of marks in five subjects.
3. Initialize an empty dictionary `total_marks`.
4. Loop through `student_marks`:
   - Calculate the total marks using `sum()`.
   - Store the result in `total_marks`.
5. Use `max()` on `total_marks` to find the student with the highest total.
6. Print:
   - The `total_marks` dictionary.
   - The **topper's name and score**.

---

## PROGRAM:
m1,m2,m3=int(input()),int(input()),int(input())<br>
total=m1+m2+m3;<br>
percentage=(total/300)*100<br>
print("Total marks obtained is {} and the percentage obtained is {}".format(total,percentage))

## OUTPUT
<img width="1156" height="177" alt="image" src="https://github.com/user-attachments/assets/3cd45b88-9549-4d76-9fcc-69820c6e3a55" />

## RESULT
Program is verified.
#  Hackerrank : #  Python Word Wrap Function
 Aim
To Develop a python program to count the number of vowels and consonants from the given string

Algorithm
1. Start Input a string s.
2. Convert the string to lowercase (to handle both uppercase and lowercase letters).
3. Initialize two counters: vowel_count = 0, consonant_count = 0. Define the set of vowels → {A, E, I, O, U, a, e, i, o, u}.
4.  For each character ch in the string: If ch is an alphabet: If ch is in vowels, increment vowel_count.
5.   Else, increment consonant_count. Display vowel_count and consonant_count.
6.   Stop

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

#  Hackerrank:Python Program to Find Students with the Second Lowest Grade

 Aim
To write a Python program to find the simple intrest.

 Algorithm
1. Start
2. Input the Principal amount P from the user.
3. Input the Rate of interest R (per annum) from the user.
4. Input the Time T in months from the user.
5. Convert Time into years: Tyear=T/12
6. Apply the formula for Simple Interest: SI=PRTyear/100
7. Display the value of SI.
8. Stop
   
 Program
```python
p=int(input())

t=float(input())

r=eval(input())

def simpleInterest(p,t,r):

si = (p*t*r)/100

return si
```
Output
<img width="1117" height="290" alt="491463809-cda51d27-bdc8-483e-8663-eea846500334" src="https://github.com/user-attachments/assets/c33ec05d-6def-49db-8c40-3eb29bbe60cd" />

## Result
Thus Python Program to Find Students with the Second Lowest Grade is excuted and verified.  is excuted and verified.
#  Hackerrank:Runner-Up Score Finder in Python

 AIM:
To write a Python program that takes a list of scores from participants and finds the runner-up score (i.e., the second-highest score), eliminating any duplicates.

 ALGORITHM:
1. Start
2. Create a variable n and get its value from the user (number of participants)
3. Read the list of n scores from the user using input().split() and convert them to integers
4. Store the scores in a list
5. Use set() to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. Stop
   
 PROGRAM:
```python
n = int(input())

arr = list(map(int, input().split()))

arr.sort()

large=arr[-1]

arr.reverse()

for i in range(len(arr)-1):

if arr[i+1]<arr[i]:

print(arr[i+1])
    break
```
## OUTPUT

![491458587-bd7dce3b-efb2-46df-9166-b3ceaae50d7e](https://github.com/user-attachments/assets/43071b4c-11b8-4855-8768-94e7c4e3f634)


## RESULT
Thus a Python program that takes a list of scores from participants and finds the runner-up score (i.e., the second-highest score), eliminating any duplicates is excuted and verified.
# Hackerrank:Python Program to Check if a String Ends with a Numeric Digit

This Python program checks whether the last character of a given input string is a **numeric digit (0–9)**.

---

##  Aim

To write a Python program that checks if a given string ends with a number using Python's built-in string methods.

---

##  Algorithm

1. **Start the program.**
2. **Input** a string from the user.
3. **Access** the last character using indexing (`string[-1]`).
4. **Check** if the last character is a digit using the `.isdigit()` method.
5. **If true**, print that the string ends with a number.
6. **Else**, print that the string does not end with a number.
7. **End the program.**

---

##   Program
```python
s = input()

c,c1,c2,c3,c4=0,0,0,0,0

for i in range(len(s)):

if s[i].isalnum():

c+=1
if s[i].isalpha():

c1+=1
if s[i].isdigit():

c2+=1
if s[i].islower():

c3+=1
if s[i].isupper():

c4+=1
if c>=1:

print('True') else:

print('False') if c1>=1:

print('True') else:

print('False') if c2>=1:

print('True') else:

print('False') if c3>=1:

print('True') else:

print('False') if c4>=1:

print('True') else:

print('False')
```
## Output

![491459635-da7de7b9-e795-4dad-98e8-ae4bc7b88864](https://github.com/user-attachments/assets/c6a0be51-5467-4ebc-9b44-d6f87f1f6150)

## Result
Thus a Python program that checks if a given string ends with a number using Python's built-in string methods is excuted and verified.
