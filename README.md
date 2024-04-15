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
###Program to find square root of a number using newton's method
###Program developed by: KATHIRESAN K
###Reg no: 212223110021
```
```
def newton_method(number,iterations=100):
    for i in range(iterations):
        number=0.5*(number+inp/number)
    return number
inp=int(input())
print("Square root of the number:",newton_method(inp))
```
## Output:
![image](https://github.com/Kathiresan-23013376/Square-root-of-a-number/assets/150008375/c2c3b041-968b-4dec-8cee-0fb50c527827)

![image](https://github.com/Kathiresan-23013376/Square-root-of-a-number/assets/150008375/26d01c3b-6b23-4e5a-9f64-0f17d54b14d1)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
