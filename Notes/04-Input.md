# Input

## What is Input?

The input() function is used to get data from the user.

## Basic Example

name = input("What is your name? ")

print("Hello", name)
### Output

What is your name? Mariam
Hello Mariam
---

## Input Always Returns a String

age = input("Enter your age: ")

print(type(age))
### Output

<class 'str'>
---

## Converting Input

### Integer

age = int(input("Enter your age: "))
### Float

height = float(input("Enter your height: "))
---

## Example

age = int(input("Enter your age: "))

print(age + 1)
---

## Notes

- input() always returns a string (str).
- Use int() for whole numbers.
- Use float() for decimal numbers.
