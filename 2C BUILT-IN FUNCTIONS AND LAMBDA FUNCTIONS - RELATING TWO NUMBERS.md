# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1.Start

2.Accept two integer inputs a and b from the user

3.Define a lambda function named result that:

4.Compares the values x and y

5.Returns:
"{x} is smaller than {y}" if x < y

"{x} is greater than {y}" if x > y

"{x} is equal to {y}" if x == y

6.Call the result function with the values a and b

7.Print the returned comparison message

8.End

---

### PROGRAM

```
result = lambda x,y : f"{x} is smaller than {y}" if x < y else (f"{x} is greater than {y}" if x > y                else f"{x} is equal to {y}")
a=int(input()) 
b=int(input())
 
# print for numbers
print(result(a, b))
```

### OUTPUT
![Screenshot (230)](https://github.com/user-attachments/assets/ea478393-a4f0-4e68-a0eb-10f8b1d9a976)

### RESULT
Thus the python program was initiated and executed successfully.
