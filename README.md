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
