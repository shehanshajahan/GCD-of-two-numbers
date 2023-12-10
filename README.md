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
Program to find the gcd of two number using function.
Developed by: Shehan Shajahan
RegisterNumber:  23008724

def gcd():
    a=int(input())
    b=int(input())
    l=[]
    if a>b:
        for i in range(1,b):
            if b%i==0:
                if a%i==0:
                    l.append(i)
        print("GCD of two numbers is:",max(l))
    else:
        for i in range(1,a):
            if a%i==0:
                if b%i==0:
                    l.append(i)
        print("GCD of two numbers is:",max(l))

```

## Output:
![gcd of two number](gcd.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
