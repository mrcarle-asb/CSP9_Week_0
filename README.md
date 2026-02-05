# Week 1: Conditionals

This week you'll complete 5 problems that all use **conditional statements** (if, if/else, if/elif/else blocks).

## Learning Resources

Don't know about conditionals yet? CS50 has you covered with multiple ways to learn:

### Full Lecture (1 hour)
**Watch the complete Week 1 lecture:**  
https://www.youtube.com/watch?v=_b6NgY_pMdw

### Read the Notes
**Skim the prepared notes if you prefer reading:**  
https://cs50.harvard.edu/python/notes/1/

### Short Videos (5-10 minutes each)
**Watch specific topics:**
- **Conditionals:** https://cs50.harvard.edu/python/shorts/conditionals/
- **Boolean Expressions:** https://cs50.harvard.edu/python/shorts/boolean_expressions/

### Jump Right In
**Or just figure stuff out as you go!** The problem descriptions will guide you.

---

## Assignment Overview

Complete **ALL** of the following problems from CS50P Week 1:

1. **Deep Thought** - The answer to life, the universe, and everything
2. **Home Federal Savings Bank** - Greetings and money
3. **File Extensions** - Determine media types
4. **Math Interpreter** - A calculator program
5. **Meal Time** - Is it time to eat?

---

## Problem 1: Deep Thought
📁 `deep/deep.py`  
🔗 https://cs50.harvard.edu/python/psets/1/deep/

Implement a program that prompts the user for the answer to the Great Question of Life, the Universe and Everything. Output `Yes` if the user inputs `42` or (case-insensitively) `forty-two` or `forty two`. Otherwise output `No`.

---

## Problem 2: Home Federal Savings Bank
📁 `bank/bank.py`  
🔗 https://cs50.harvard.edu/python/psets/1/bank/

Implement a program that prompts the user for a greeting:
- If the greeting starts with `"hello"`, output `$0`
- If the greeting starts with `"h"` (but not `"hello"`), output `$20`
- Otherwise, output `$100`

Ignore any leading whitespace in the user's greeting, and treat it case-insensitively.

---

## Problem 3: File Extensions
📁 `extensions/extensions.py`  
🔗 https://cs50.harvard.edu/python/psets/1/extensions/

Implement a program that prompts the user for a file name and outputs that file's media type if the file's name ends (case-insensitively) in any of these suffixes:

- `.gif`
- `.jpg`
- `.jpeg`
- `.png`
- `.pdf`
- `.txt`
- `.zip`

If the file's name ends with some other suffix or has no suffix at all, output `application/octet-stream`.

---

## Problem 4: Math Interpreter
📁 `interpreter/interpreter.py`  
🔗 https://cs50.harvard.edu/python/psets/1/interpreter/

Implement a program that prompts the user for an arithmetic expression and then calculates and outputs the result as a floating-point value formatted to one decimal place.

**Assumptions:**
- User's input will be formatted as `x y z` (with spaces)
- `x` is an integer
- `y` is `+`, `-`, `*`, or `/`
- `z` is an integer
- If `y` is `/`, then `z` will not be 0

**Example:** If the user inputs `1 + 1`, your program should output `2.0`.

---

## Problem 5: Meal Time
📁 `meal/meal.py`  
🔗 https://cs50.harvard.edu/python/psets/1/meal/

Implement a program that prompts the user for a time and outputs whether it's breakfast time, lunch time, or dinner time. If it's not time for a meal, don't output anything at a
