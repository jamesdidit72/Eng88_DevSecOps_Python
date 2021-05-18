#Python
##Python installation 3.7 or above
### Pycharm set up
#### Documentation with README.md to store on Git-hub

- Testing the python env `print("Welcome to Engineering 88!")`
#### What is Python and how does it link to DevSecOps
- Easily readable high level language
- Transferable coding language with other languages
- Uses OOP (Object oriented programing)
#### What are variables
- Placeholders to store data
- strings, booleans, integers
    - "This is a string" "" or ' '
    - Boolean is True or False (case sensitive)
    - Integers is a number    
    
```python
first_name = "James"
last_name = "Barton"
age = 22
print(first_name)
print(last_name)
print(age)
print(first_name, last_name, age)
# how to find the variable
print(type(first_name))
print(type(last_name))
print(type(age))
print(type(wage))
```

###Operators

| Operand | Description | Example |
|:---------: |:----------------------------: |:--------: |
| + | add two operands (variables) together| X + y + 2 |
| - | subtract two operands (variables) | X - y - 2 |
| * | multiply two operands (variables) | X - y - 2 |
| / | divide two operands (variables) | X - y - 2 |
| % | Modulus - remainder of the division of left operand by the right | X - y - 2 |
| + | add two operands (variables) together| X + y + 2 |



## Comparison Operators



| Operand | Description | Example |
|:---------: |:----------------------------: |:--------: |
| > | True if left operand is greater than the right| x > y |
| < | True if left operand is less than the right| x < y |
| == | True if both operands are equal | x == y |
| != | True if both operands are equal | x != y |
| >= | True if left operand is greater than or equal to the right| x >= y |
| <= | True if left operand is less than or equal to the right| x <= y |

####initial operators work
```python
value_1 = 6
value_2 = 7

print(value_2 > value_1)
name = "James"
age = 22
print(name.isalpha())  # isalpha checks if the value is alphabetical
print(name.isdigit())  # checks the value if it is a digit
print(name.startswith("J"))  # checks what the first letter begins with
```