# user-input-and-type-casting-python-internship-2


# Documentation: Age Input and Years to Reach 100

## Objective

This program demonstrates how to:

* Accept user input using the `input()` function.
* Convert string input into an integer using `int()`.
* Perform arithmetic operations.
* Display formatted output using an f-string.

## Program Code

```python
# Converting input to an integer
age = int(input("Enter your age: "))

# Now you can do math with it
years_left = 100 - age
print(f"You will turn 100 in {years_left} years!")
```

## Explanation

### 1. Accept User Input

```python
age = int(input("Enter your age: "))
```

* `input()` prompts the user to enter their age.
* By default, `input()` returns the value as a string.
* `int()` converts the entered string into an integer so mathematical operations can be performed.

### 2. Calculate Remaining Years

```python
years_left = 100 - age
```

* The program subtracts the user's current age from `100`.
* The result is stored in the variable `years_left`.

### 3. Display the Result

```python
print(f"You will turn 100 in {years_left} years!")
```

* An f-string (`f"..."`) is used to insert the value of `years_left` directly into the output message.
* The message is displayed in a readable format.

## Sample Execution

**Input:**

```
Enter your age: 25
```

**Output:**

```
You will turn 100 in 75 years!
```

## Key Concepts Used

* `input()` – Reads input from the user.
* `int()` – Converts a string to an integer.
* Arithmetic operator (`-`) – Performs subtraction.
* Variables – Store user input and calculation results.
* f-strings – Format output by embedding variable values in strings.

## Conclusion

This program illustrates basic user interaction in Python by accepting input, converting it to the appropriate data type, performing a calculation, and presenting the result in a clear and formatted message.
