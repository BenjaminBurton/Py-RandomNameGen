# Python Random Name Generator

Overview:

Import Libraries: Utilize the random library to generate random selections.

Create Name Lists: Define lists of first names and last names

Random Selection Function: Write a function to randomly select a first name and a last name.

Combine Names: Combine the selected first and last name into a full name.

Output the Name: Print or return the generated random name.

```
Python

import random

# Step 2: Create Name Lists
first_names = ["Alice", "Bob", "Charlie", "Diana"]
last_names = ["Smith", "Jones", "Brown", "Taylor"]

# Step 3: Random Selection Function
def generate_random_name():
    first_name = random.choice(first_names)
    last_name = random.choice(last_names)
    # Step 4: Combine Names
    return f"{first_name} {last_name}"

# Step 5: Output the Name
print(generate_random_name())
```
