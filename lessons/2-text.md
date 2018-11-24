# 2. Working with text

## 2.1. Getting started

> A text string, also known as a string or simply as text is a group of characters

- Strings can be assigned to variables: `x = "Hello, world!"`
- Square brackets can be used to access characters (symbols) of the string: `x[1]` returns `e`
- A **substring** is a smaller part of a string: `x[1:4]` returns `ell`
- You can use `+` operator to add strings together
  `x + y` or `x + "another text"` or `"another" + " " + "text"`

## 2.2. String methods

*Methods can be used to get a new modified value of the string*

*Methods can be called on a string literal:`"Hello".strip()` or on a
variable that has a string value: `x.strip()`*

- The strip() method removes any whitespace from the beginning or the end
  <br>`"  Hello! ".strip()` returns `Hello!`
- The lower() method returns the string in lower case
  <br>`x.lower()` returns `hello, world!`
- The upper() method returns the string in upper case
  <br>`x.upper()` returns `HELLO, WORLD!`
- The len() method returns the length of a string
  <br>`len(x)` returns `13`
- The `replace()` method replaces a string with another string
  <br>`x.replace("l", "r")` returns `Herro, worrd!`
- The split() method splits the string into substrings if it finds instances of the separator
  <br>`a.split(",")` returns `["Hello", "World!"]

## 2.3. String input

*`input()` function by default returns a string of text thet user entered*

*[Follow the tutorial](https://www.w3schools.com/python/python_strings.asp)*

### Final Exercise 1

- Create a command line application that:
  - Asks the user to enter his/her name
  - Asks the user to enter his/her last name
  - Asks user to enter his/her age
  - Prints a formatted message (with user entered info):
  <br>`J. Smith is 42 years old`
- *Note:* Get the first letter of the name and put a dot (.) after it

### Final Exercise 2

- Create a command line application that:
  - Asks the user to enter his/her five favourite foods, spearated by
    commas (,), e.g. `Pizza, Steak , Noodles,  Burgers, Pasta`
  - Print the 3rd favourite food, e.g. `Noodles`
- *Note:* You'll need `split()` and `strip()` methods