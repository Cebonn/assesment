Section 1 — Data types & variables
Q1
Data types
1 pt
What will the following code print? Explain why in one sentence.

x = "5"
y = 3
print(x * y)
555.  5 being a string hinders the occurrence of an arithmetic action therefore * initiates repetition of the string
Q2
Lists & references
1 pt
What is the output of this code, and what Python concept does it demonstrate?

a = [1, 2, 3]
b = a
b.append(4)
print(a)
[1, 2, 3, 4]
Q3
Dictionaries
1 pt
Write a function called word_freq(words) that takes a list of words and returns a dictionary mapping each word to how many times it appears.


    def word_freq(words):
    freq = {}
    for word in words:
        if word in freq:
            freq[word] += 1
        else:
            freq[word] = 1
    return freq

Section 2 — Functions & scope
Q4
Default arguments
1 pt
Identify the bug in this function and write the corrected version.

def add_item(item, items=[]):
    items.append(item)
    return items
Explain the bug, then write the fix...
Q5
Lambda & sorting
1 pt
Sort this list of dictionaries by the 'score' key in descending order using a single line of code.

players = [
    {"name": "Alice", "score": 82},
    {"name": "Bob",   "score": 95},
    {"name": "Cara",  "score": 78},
]
sorted_players = ...
Q6
Decorators
1 pt
Write a decorator called timer that measures and prints how long a function takes to run.

import time

def timer(func):
    # your code here
Section 3 — Object-Oriented Programming
Q7
Classes
1 pt
Build a BankAccount class with a balance attribute, a deposit() method, and a withdraw() method that raises a ValueError if there are insufficient funds.

class BankAccount:
    # your code here
Q8
Inheritance
1 pt
Explain what this code prints and why. Reference the concept of method resolution order (MRO) in your answer.

class Animal:
    def speak(self):
        return "..."

class Dog(Animal):
    def speak(self):
        return "Woof"

class Cat(Animal):
    pass

print(Dog().speak())
print(Cat().speak())
Write your explanation here...
Section 4 — Error handling & file I/O
Q9
Try / except / finally
1 pt
What does the code below print? Then extend it by adding a finally block that always prints "Done."

try:
    result = 10 / 0
except ZeroDivisionError:
    print("Can't divide by zero")
except Exception as e:
    print(f"Error: {e}")
Output: ...

With finally block:
# write the updated code here
Q10
File I/O & JSON
1 pt
Write code to read a JSON file called config.json and safely handle the case where the file does not exist — returning an empty dict as the default.

import json

# your code here
Section 5 — Python for AI (practical)
Q11
List comprehensions
1 pt
Rewrite the following loop as a single-line list comprehension.

results = []
for score in scores:
    if score >= 50:
        results.append(score * 1.1)
results = ...
Q12
Generators
1 pt
Explain the difference between a list and a generator in terms of memory. Then write a generator function that yields the first N Fibonacci numbers.

Explanation: ...

def fibonacci(n):
    # your code here
Q13
Security & .env
1 pt
You need to store an API key and use it in Python without exposing it in your code or Git history. Show the wrong approach, explain the risk, then show the correct approach using python-dotenv.

Wrong approach:
# ...

Risk: ...

Correct approach:
# ...
Q14
Virtual environments
1 pt
Write the terminal commands to: (1) create a virtual environment, (2) activate it on Mac/Linux, (3) install the openai package, and (4) save all dependencies to a file.

# 1. Create
# 2. Activate
# 3. Install
# 4. Save
Q15
Debugging
1 pt
This function is supposed to return the average of a list. Find all the bugs and write the corrected version with edge case handling.

def get_average(nums):
    total = 0
    for n in nums:
        total =+ n
    return total / len(nums)
Bugs found:
1. ...
2. ...

Corrected function:
def get_average(nums):
