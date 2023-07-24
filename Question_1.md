#science 
[[PAT Github]]
[[Projects]]
[[Firebrand]]

# Question:
You have the following snippet:
x = 8
y = 4.00

print(type(x + y))

What will the above code print?

A. class <'int'>
B. 12.00
C. 12
D. <class 'float'>


# Hint:
The type() function is an important factor in the answer. 


# Answer:
The above code will print the answer:
- D. <class 'float'> 
Because of the line print(type(x + y)) which is used with the function type() and the sum of two variables int and float converts into float.

The above code will not print the answer:
- A. class <'int'>
This would be true if the variable y was an integer 4, instead of float 4.00 

The above code will not print the answer:
- B. 12.00
This would be true if the print() statement would be used with just the sum of variables x and y in the way shown below:
print(x + y)
The statement was used with function type() which is designed to show the type of variable, not its value.

The above code will not print the answer:
- C. 12
This would be true if the print() statement would be used with just the sum of variables x and y in the way shown below:
print(x + y) and both of the variables would be integers. The value of y is float which means the result of the sum of x and y is converted into float.