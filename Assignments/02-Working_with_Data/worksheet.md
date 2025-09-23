# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:` We'd have to use .append()

2. How can you remove an item from a list by value?

   `Answer:` We'd use .remove(value)

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` [2, 4, 6, 8]

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
foods = ["seafood", "pasta", "tacos"]

# Add another food to the list.
foods.append("barbeque")

# Remove one item and print the list.
foods.remove("pasta")
print(foods)
```

---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` A list can be modified after created, while tuples cannot be
   modified once created.

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` No, because we will receive a TypeError.

---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
numbers = (4, 8, 21)

# Unpack it into three variables and print each.
a, b, c = numbers
print(a)  
print(b) 
print(c)  
```

---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly? 

   `Answer:` It returns a default value for a missing key.

7. How do you loop through both keys and values in a dictionary?  

   `Answer:` Use .item() for loops.

---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
person = {"name": "Aniah", "age": 23, "hobby": "basketball"}

# Print each key and value in the format "key: value".
for key, value in person.items():
    print(f"{key}: {value}")
```

---

## 🧾 Submit Checklist

- [ ] I practiced creating and modifying lists.
- [x] I understand how tuples are different from lists.
- [ ] I accessed and looped through dictionary items.