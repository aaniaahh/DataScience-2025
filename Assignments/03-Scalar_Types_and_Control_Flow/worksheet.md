# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:` <class 'int'>

2. What scalar type would best represent:
   - A person's name: str
   - Their age: int
   - Whether they passed a test: bool

---

### ✏️ Task: Type Practice

```python
# Create a variable for each type and print its value and type
# Example: an int, float, str, and bool
# Create a variable for each type and print its value and type

age = 36          # int
height = 6.2      # float
name = "Chris"    # str
passed = True     # bool

print(age, type(age))
print(height, type(height))
print(name, type(name))
print(passed, type(passed))

```

---

## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` Not equal to

4. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:` True, because 5 < 3 = False OR 3 < 10 so False or True = True.

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python
if grade >= 70:
    print("Pass")
elif:
print("Fail")
```

6. What does `elif` allow you to do?

`Answer:` It checks for any additional conditions. (i.e. "else if" in c++)

---

### ✏️ Task: Your Turn

Write a program that asks for the weather and prints:
- "Bring sunscreen" if it's sunny
- "Take an umbrella" if it's raining
- "Check the forecast" otherwise

``` python
# Ask for grade input
weather = int(input('What is the weather like today? '))

# Use if else statement to give grade letter
if weather == "sunny":
  print("Bring sunscreen!")
elif weather == "rainy":
  print("Take an umbrella.")
else:
  print("Check the forecast.")
```