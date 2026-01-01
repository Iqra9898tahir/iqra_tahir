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
