# 1. Starting with maths

## 1.1. Getting started

> Python is an interpreted programming language, this means that as a developer you write Python (.py) files in a text editor and then put those files into the python interpreter to be executed.

*[Follow the tutorial](https://www.w3schools.com/python/python_getstarted.asp)*

#### Exercise 1 

- In your command line, run `python helloworld.py` (you should've created the file in the tutorial above)

## 1.2. Basic syntax

> In programming, syntax refers to the **rules** that specify the correct combined sequence of symbols that can be used to form a correctly structured program.

- Indentation
- Comments

*[Follow the tutorial](https://www.w3schools.com/python/python_syntax.asp)*

## 1.3. Variables

> In computer programming, variables are used to store information to be referenced and used by programs. 

- Creating variables
- Setting variables
- `print`ing values to the console

*[Follow the tutorial](https://www.w3schools.com/python/python_variables.asp)*

#### Exercise 2

- Create variable `x` with value `6`
- Assign `x` a new value, `42`
- Print `x` to the console

### 1.3.1. User input

- You can ask user to type in some text with `input()` statement
- By default, `input()` will return a **string** type text value
- To get a **number** out of `input()` use **casting**:
  - `z = int(input())` *(user typed "3")* - `z` will be `3` (integer)
  - `z = float(input())` *(user typed "3")* - `z` will be `3.0` (floating point number)
  - `w = float(input())` *(user typed "4.2")* - `w` will be `4.2` (floating point number)
- **Note**: For better UX, you should first inform the user, what kind of input is needed, e.g.:

```python
print("Please enter your age")
age = int(input())
```

#### Exercise 3

- Get user entered **integer** and save it to variable `x`
- Assign `x` to `x * 4`
- Print `x` to the console

## 1.4. Numbers

- There are three numeric types in Python:
  - int
  - float
  - complex

*[Follow the tutorial](https://www.w3schools.com/python/python_numbers.asp)*

## 1.5. Arithmetic operators

> Operators are used to perform operations on variables and values

- `+` Addition
- `-` Subtraction
- `*` Multiplication
- `/` Division
- `%` Modulus
- `**` Exponentiation
- `//` Floor division

*[Follow the tutorial](https://www.w3schools.com/python/python_operators.asp)*

### Final exercise 1

Create a command line application that can be used to calculate the
Discriminant for a square equation.

- Save user input in `float` variables `a`, `b` and `c`
- Calculate **discriminant** and save it to variable `D`
  (you will need to write the formula using Arithmetic operators)
- Print `D` to the console

### Final exercise 2

Create a command line application that can be used to calculate the
"speed of sedimentation".

- Save user input in `float` variables `rho1`, `rho2`, `d`, `eta`
- Calculate **speed of sedimentation** and save it to variable `v`
  (you will need to write the formula using Arithmetic operators)
- Print `v` to the console