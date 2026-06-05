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
string=input()
n=int(input())
es=''
for i in range(len(string)):
    if i!=n:
        es+=string[i]
print(es)
```
## Output
<img width="383" height="295" alt="600895512-6a8351ae-5919-4dcb-8694-482511688470" src="https://github.com/user-attachments/assets/31388857-a45c-4ed2-b7d1-44f95c3b3d6e" />


## Result
Successfully wrote a Python program that accepts a string and removes the character at a specified index.
