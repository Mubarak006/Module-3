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
# Step 1: Import the re module
import re

# Step 2: Initialize an empty list to store results
l1 = []

# Step 3: Define a list of words
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

# Step 4: Iterate through each word in the list
for i in items:
    # If 'e' is NOT found in the word, add it to l1
    if not re.search(r"e", i):
        l1.append(i)

# Step 5: Print the final filtered list
print("Words that do not contain the letter 'e':", l1)
```
## Output

![image](https://github.com/user-attachments/assets/4b059619-c0d9-4357-ae41-1b99228080bc)


## Result
This program successfully filters out and returns all elements that do not contain the letter 'e' using regular expressions.
