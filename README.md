# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Surendhar A
RegisterNumber:  212222110049
*/
def sqroot():
    num1=int(input())
    num2=float(num1)
    for i in range (100):
        num1=0.5*(num1+num2/num1)
    print("Square root of the number:",num1)
sqroot()
```

## Output:
![image](https://github.com/Surendhar6/Square-root-of-a-number/assets/118352907/82b4350a-cd74-4a86-b3e1-22753c1ce817)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
