# 📝 Worksheet: 04 - Loops and Iteration

Practice and reflect on how loops work in Python.

---

## 🔁 Section 1: For Loops

1. What does `range(5)` produce?

`Answer:` 0, 1, 2, 3, 4

2. Write a `for` loop that prints numbers 1 to 10, but skips 5.

```python
for i in range(1, 11):
    if i == 5:
        continue
    print(i)
```

---

## 🔁 Section 2: While Loops

3. What’s the difference between a `for` loop and a `while` loop?

`Answer:`A for loop continues for a number a times, and a while loop continues as long
as the conditions is true.

4. What happens if a `while` loop's condition never becomes `False`?

`Answer:` The loop will run forever.

---

### ✏️ Task: Countdown with While

```python
# Use a while loop to count down from 5 to 1.
n = 5
while n > 0:
    print(n)
    n -= 1
```

---

## 📁 Section 3: File Reading and `with`

5. What does the `with` statement do when opening a file?

`Answer:` It properly opens and closes a file automatically.

6. How do you loop over each line in a file?

``` python
for line in f:
    # process line
```

---

### ✏️ Task: File Filter

Write code that prints only the lines in a file that contain the word `"error"`.

```python
with open("data.txt", "r") as f:
    for line in f:
        if "error" in line:
            print(line.strip())
```