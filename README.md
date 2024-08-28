# Even and Odd Number Filter

## Overview

This project demonstrates how to filter even and odd numbers from a list using Python.

## How It Works

- **Even Numbers:** The script uses the `filter()` function with a lambda expression to filter out even numbers from a list.
- **Odd Numbers:** It also filters out odd numbers using the same method.

## Code Example

```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

even_numbers = list(filter(lambda x: x % 2 == 0, numbers))
odd_numbers = list(filter(lambda x: x % 2 == 1, numbers))

print(even_numbers)  # Output: [2, 4, 6, 8, 10]
print(odd_numbers)   # Output: [1, 3, 5, 7, 9]
```

## How to Run

1. Make sure Python is installed on your machine.
2. Download the script file.
3. Run the script using the command:
   ```bash
   python main.py
   ```
   Replace `main.py` with the actual name of your file.

## Output

The script will print two lists:
- Even numbers: `[2, 4, 6, 8, 10]`
- Odd numbers: `[1, 3, 5, 7, 9]`