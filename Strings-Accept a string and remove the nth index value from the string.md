
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
def remove(str): 
l=len(str) 
a="" 
n=int(input()) 
for i in range(0,l): 
if i==n: 
a=a+"" 
else: 
a=a+str[i] 
print(a)
```
## Output

![image](https://github.com/user-attachments/assets/a476aee1-7a07-4785-84dd-eb04b3b12941)


## Result
Thus,the program has been executed successfully.
