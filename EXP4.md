# Ex.No: 4 Check the given number is Armstrong number or not and inspect for failures.
### DATE: 06.09.2024                                                                           
### REGISTER NUMBER : 212221040157
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:

```
x = input()

if x.isnumeric():
    x = int(x)  
    temp = x
    cube_sum = 0

    while temp > 0:
        digit = temp % 10
        cube_sum += digit ** 3  
        temp //= 10  

    if cube_sum == x:
        print("Armstrong Number")
    else:
        print("Not an Armstrong Number")
else:
    print("Enter a positive integer.")
```

### Output:

<img width="959" alt="ex4" src="https://github.com/user-attachments/assets/ede266bb-191b-4a52-95ff-0106d6653367">


### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


