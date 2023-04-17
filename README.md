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
#Program to find gcd of two number using function.
#Developed by:Pravin raj.A
#RegisterNumber:212222240079

def gcd():
    num1,num2=int(input()),int(input())
    if num1>num2:
        smaller=num2
    else:
        smaller=num1
    for i in range(1,smaller+1):
        if num1%i==0 and num2%i==0:
            gcdvalue=i
    print("GCD of two numbers is:",gcdvalue)

```

## Output:

![Screenshot_20230417_095219](https://user-images.githubusercontent.com/118707879/232377654-063077af-3dc3-4ccb-9b74-7a2cb697435b.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
