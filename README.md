# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by:saranya s 
RegisterNumber: 23013399 
*/
def gcd():
    num1=int(input())
    num2=int(input())
    if num1>num2:
        min=num2
    else:
        min=num1
    for i in range(1,min+1):
        if(num1%i==0 and num2%i==0):
           gcd=i
    print("GCD of two numbers is:",gcd)
```

## Output:
![gcd of two number](gcd.png)
![image](https://github.com/srisrisaranya/GCD-of-two-numbers/assets/148516638/2d94773f-f52c-46ce-ad75-221711921bff)

![image](https://github.com/srisrisaranya/GCD-of-two-numbers/assets/148516638/d6a84c05-e2a4-46d5-b6ca-0e7dea24957d)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
