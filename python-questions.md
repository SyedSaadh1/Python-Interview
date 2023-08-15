### 1. **Question**: What are list comprehensions in Python?
   - **Answer**: List comprehensions provide a concise way to create lists in Python. They can be used to generate a new list by performing some operation on each item in an existing list (or other iterables) and filtering the items based on a condition. For example, `[x**2 for x in range(10) if x%2 == 0]` creates a list of squares for even numbers between 0 and 9.

### 2. **Question**: How is memory managed in Python?
   - **Answer**: Python manages memory using a private heap. All objects and data structures are located in this private heap, and the programmer does not have access to it. However, Python provides an interface to tools in the core API for programmers to code. Python also has an inbuilt garbage collector, which recycles all the unused memory to ensure that the heap is free from unused memory.

### 3. **Question**: Describe the difference between a tuple and a list in Python.
   - **Answer**: Both tuples and lists are used to store collections of items in Python. The main differences are that tuples are immutable, meaning their values cannot be changed after they are created, while lists are mutable. Tuples use parentheses `()` while lists use square brackets `[]`. Because tuples are immutable, they can be used as keys in dictionaries, while lists cannot.

### 4. **Question**: What's the difference between `deepcopy` and `copy` in Python?
   - **Answer**: In Python, `copy` creates a shallow copy of an object. For compound objects like lists or dictionaries, a shallow copy creates a new object, but does not create copies for the objects found within the original. `deepcopy`, on the other hand, creates a new object and recursively adds copies of objects found in the original. This means changes to the inner objects of the original won't affect the deepcopy and vice-versa.

### 5. **Question**: How do you handle exceptions in Python?
   - **Answer**: In Python, exceptions can be handled using a try-except block. The potentially error-causing code is placed inside the `try` block. If an error occurs, the code inside the `except` block is executed. There's also an optional `finally` block that can be used to define cleanup actions, which always get executed, regardless of whether an error occurred.

