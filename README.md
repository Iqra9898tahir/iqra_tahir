# Reverse a String – Python Beginner Example

This is a **beginner-friendly Python code** to reverse a string.  
The code is explained **step by step** for easy understanding and interview preparation.

---

## Goal
Reverse the string `"automation"` → `"noitamotua"`

---

## Python Code

```python
# Original text
text = "automation"

# Empty string to store reversed text
reverse = ""

# Loop through each character in the text
for ch in text:
    # Add current character in front of the reverse string
    reverse = ch + reverse

# Print the reversed text
print(reverse)
```
## Palindrome Check
```python
# Original word
word = "madam"

# Empty string to store reversed word
reverse = ""

# Loop through each character in the word
for ch in word:
    reverse = ch + reverse

# Compare original word with reversed word
if word == reverse:
    print("Palindrome")
else:
    print("Not Palindrome")
```
# FIND DUPLICATE CHARACTERS
```python
text = "selenium"

checked = ""
duplicates = ""

for ch in text:
    if ch in checked:
        if ch not in duplicates:
            duplicates = duplicates + ch
    else:
        checked = checked + ch

print(duplicates)
```
# Count each character
```python
text = "test"

for ch in text:
    count = 0
    for c in text:
        if ch == c:
            count = count + 1
    print(ch, count)
```
```python
# Original word
text = "test"

# Empty dictionary to store counts
counts = {}

# Loop through each letter
for ch in text:
    if ch in counts:
        counts[ch] = counts[ch] + 1  # Increase count if already exists
    else:
        counts[ch] = 1  # First time, set count as 1

# Print the result
print(counts)
```
# Largest Number
```python
numbers = [4, 7, 2, 9, 5]

# Assume first number is largest
largest = numbers[0]

# Check every number in the list
for num in numbers:
    if num > largest:
        largest = num

print("Largest number is:", largest)
```
# Find smallest no
```python
numbers = [4, 7, 2, 9, 5]

# Assume first number is smallest
smallest = numbers[0]

# Check every number in the list
for num in numbers:
    if num < smallest:
        smallest = num

print("Smallest number is:", smallest)
```
# Add total numbers
```python
numbers = [4, 7, 2, 9, 5]

# Start with total = 0
total = 0

# Add each number to total
for num in numbers:
    total = total + num

print("Sum of all numbers is:", total)
```
# Reverse a string
```python
text = "selenium"
reversed_text = ""

# Start from the last letter to the first
for i in range(len(text)-1, -1, -1):
    reversed_text = reversed_text + text[i]

print("Reversed string is:", reversed_text)
```
# COUNT OCCURRENCES OF EACH ELEMENT IN A LIST
```python
numbers = [1, 2, 2, 3, 1, 2]

counted = []

for num in numbers:
    if num not in counted:
        count = 0
        for n in numbers:
            if n == num:
                count = count + 1
        print(num, "appears", count, "times")
        counted.append(num)
```
