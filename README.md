# task4-Functions-for-Reusable-Data

## Description
Create reusable Python functions for calculations, data transformation, and simple statistical operations.

## Objective
Learn how functions improve code organization and reusability.

## Tools
- Python
- Jupyter Notebook

## Deliverables
- At least five custom functions
- Functions for calculating mean, maximum, minimum, and percentage
- Examples showing function parameters and return values

## Mini Guide
- Use `def` to define functions.
- Use parameters for reusable logic.
- Return calculated values instead of only printing them.

## Suggested Datasets
- Student Marks Dataset
- Employee Dataset

## Example Python Functions

```python
def calculate_mean(numbers):
    return sum(numbers) / len(numbers) if numbers else 0

def find_maximum(numbers):
    return max(numbers) if numbers else None

def find_minimum(numbers):
    return min(numbers) if numbers else None

def calculate_percentage(obtained, total):
    if total <= 0:
        raise ValueError("Total marks must be greater than zero.")
    return (obtained / total) * 100

def convert_to_uppercase(text):
    return text.upper()

# Examples
marks = [80, 75, 90, 85, 70]
print("Mean:", calculate_mean(marks))
print("Maximum:", find_maximum(marks))
print("Minimum:", find_minimum(marks))
print("Percentage:", calculate_percentage(360, 400))
print("Uppercase:", convert_to_uppercase("python"))
```

## Interview Questions
1. What is a function in Python?
2. What is the difference between a parameter and an argument?
3. What is the purpose of the `return` statement?
4. Why are reusable functions useful?
5. What happens when a function has no explicit return statement?
