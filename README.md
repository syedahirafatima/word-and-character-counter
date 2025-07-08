# words and characters counter in Python
A simple Python program that counts the total number of words and characters in any sentence or paragraph entered by the user.


# Features:

1. Counts total characters (including spaces)
2. Counts total words
3. Takes user input from the terminal
4. Beginner-friendly code (no f-strings used)

# Code Breakdown:

```python
# Take input from the user
text = input("Enter a sentence or paragraph: ")
```

☝️ This line prompts the user to type something and stores it in a variable called `text`.

```python
# Count characters and words
character_count = len(text)
word_count = len(text.split())
```

☝️ * `len(text)` counts **all characters** (including spaces and punctuation).
* `text.split()` breaks the input into a list of words (split by spaces), and `len(...)` counts the number of words.

```python
# Display results without using f-strings
print("Total characters:", character_count)
print("Total words:", word_count)
```

☝️ This prints the character and word count using commas instead of formatted strings.

# Requirements:

Python 3.x
(No external libraries needed)

# Example:

```bash
Enter a sentence or paragraph: Python is fun to learn!
Total characters: 25
Total words: 5
```

# How to Run

1. Save the file as `word_counter.py`
2. Open terminal or command prompt
3. Run the script:

```bash
python word_counter.py
```

# What I Learned:

1. How to use `input()`, `len()`, and `split()`
2. Basic string operations in Python
3. Displaying output with commas (no f-strings)
4. Clean code structure using simple logic

Licensed under the MIT License.
