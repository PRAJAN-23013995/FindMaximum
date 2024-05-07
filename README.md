# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
#developed by: PRAJAN P
#reg no: 212223240121
def max_marks(array):
    array.sort()
    return array[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
#developed by: PRAJAN P
#reg no: 212223240121
def max_marks(array):
   return max(array)
```

iii) # To find the maximum marks without using builtin functions.
```Python
#developed by: PRAJAN P
#reg no: 212223240121
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```



## Output:
![Screenshot 2024-05-07 202020](https://github.com/PRAJAN-23013995/FindMaximum/assets/150313345/187cafd0-2bae-439e-94eb-fb70ed11ff50)

![Screenshot 2024-05-07 202033](https://github.com/PRAJAN-23013995/FindMaximum/assets/150313345/bea0b983-232a-4e09-8e8e-c64768c08fff)

![Screenshot 2024-05-07 202048](https://github.com/PRAJAN-23013995/FindMaximum/assets/150313345/95441b35-7097-4424-9dcb-9fd9a163f121)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
