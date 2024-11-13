# Day 5: String Extraction and Concatenation
## *Task: Extract parts of a string and perform concatenation.*

*Description*:
Strings in Python allow you to access individual sections, which can then be printed or manipulated as needed. In this task, you’ll first extract a part of a string and print it, and then concatenate it with another string to form a modified phrase.

Question:
Write a Python program that does the following:

    Define a variable text and assign it the value "hello world".
    Extract the word "world" from text and print it.
    Concatenate "world" with the word "everyone" to form the new phrase "world everyone", and store this in a new variable named new_text.
    Display the final modified text with a label (e.g., “The modified text is: world everyone”).

Example:
```python
# Define the variable
text = "hello world"

# Extract the word "world" and print it
extracted_word = text[6:]
print(extracted_word)

# Concatenate with "everyone" to form a new phrase
new_text = extracted_word + " everyone"

# Display the result with a label
print("The modified text is:", new_text)

Expected Output:

world
The modified text is: world everyone