# Age Calculator

This Python script calculates a person's age 5 years into the future.

## How It Works

1. **Introduction**: The program informs the user that it will calculate their age 5 years from now.
2. **Age Input**: The user provides their current age.
3. **Future Age Calculation**: The script adds 5 years to the current age.
4. **Display Future Age**: The script displays the age the person will be in 5 years.

## Example

```python
# Introduction
print('Let\'s find out your age in 5 years!')

# Reading the current age
age = int(input('Enter your age: '))

# Adding 5 years
future_age = age + 5

# Displaying the future age
print(f'In 5 years, you will be {future_age} years old!')
