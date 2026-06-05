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
l=[]
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r'e',i):
        l.append(i)
print(l)
```
## Output
<img width="641" height="247" alt="600894833-219f94ef-50ad-4081-959e-42b3e2a7492a" src="https://github.com/user-attachments/assets/5d5102e1-7cc2-4dd6-8456-cb31775c7fff" />


## Result
Successfully wrote a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).
