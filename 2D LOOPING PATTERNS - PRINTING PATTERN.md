# Exp.No:2d
## LOOPING PATTERNS -  PYTHON PROGRAM TO PRINT REVERSE NUMBER TRIANGLE PATTERN

---

### AIM  
To write a Python program that prints a triangle pattern of numbers in reverse order for each row based on the number of rows entered by the user.


### ALGORITHM

1.Start

2.Get the number of rows from the user and store it in rows

3.Use an outer for loop from 1 to rows - 1:

4.For each row i, use an inner loop to print numbers in reverse from i to 1

5.Print each number with a space using end=' '

6.After inner loop ends, use print("") to move to the next line

7.End

---

### PROGRAM
```
rows = int(input())
for i in range(1, rows):
    for j in range(i, 0, -1):
        print(j, end=' ')
    print("")

```

### OUTPUT
![Screenshot (231)](https://github.com/user-attachments/assets/9d23887c-ca3b-4e39-9ecc-c802a2e8983f)

### RESULT
Thus the python program was initiated and executed successfully.
