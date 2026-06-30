# Type Casting

## What is Type Casting?

Type casting means converting a value from one data type to another.

---

## Convert String to Integer

age = "16"

age = int(age)

print(age)
print(type(age))
Output:

16
<class 'int'>
---

## Convert Integer to Float

number = 25

number = float(number)

print(number)
print(type(number))
Output:

25.0
<class 'float'>
---

## Convert Float to Integer

height = 1.85

height = int(height)

print(height)
Output:

1
> Note: int() removes the decimal part; it does not round the number.

---

## Convert Number to String

score = 95

score = str(score)

print(score)
print(type(score))
Output:

95
<class 'str'>
---

## Common Type Casting Functions

| Function | Converts To |
|----------|-------------|
| int() | Integer |
| float() | Float |
| str() | String |
| bool() | Boolean |

---

## Notes

- input() always returns a string.
- Use int() for whole numbers.
- Use float() for decimal numbers.
- Use str() to convert numbers into text.

---

## Practice

1. Convert "100" to an integer.
2. Convert "3.14" to a float.
3. Convert 50 to a string.
4. Print the data type after each conversion.
