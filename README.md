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
Developed by:Devesh s 
RegisterNumber:23004345  
*/
```
def n(num,num1=100):

    a=float(num)
    
    for i in range(num1):
    
        num=0.5*(num+a/num)
        
    return num
    
a=int(input())  

print("Square root of the number:",n(a))


## Output:
![Screenshot 2024-01-01 114126](https://github.com/23004345/Square-root-of-a-number/assets/138849203/0c53483a-01e7-4d44-9828-0d05c71a9f41)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
