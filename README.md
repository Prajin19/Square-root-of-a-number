# Square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Define a function.
### Step 2:
Assign number_iters = 100 in the function to perform 100 iteratios.
### Step 3:
Set i = 0.
### Step 4:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
### Step 5:
Return number

## Program:
```
#Square root of a number
#Developed by: Prajin S
#Register number: 23012918
def newton(no,noiter=100):
    a=float(no)
    for i in range(noiter):
        no=.5*(no+a/no)
    return no
a=int(input())
print('Square root of the number:',newton(a))
```

## Output:
![Square root](https://github.com/Prajin19/Square-root-of-a-number/assets/144979377/734d5424-effc-4ace-b45b-79387ce077a4)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
