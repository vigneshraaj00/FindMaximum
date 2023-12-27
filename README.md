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
```
Program to mark the maximum of marks using the list method sort
Developed by:vignesh raaj s 
RegisterNumber: 23005346
def max_marks(marks):
    marks.sort()
    b=marks[-1]
    return b
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: vignesh raaj s
RegisterNumber: 23005346
def max_marks(marks):
    a=max(marks)
    return a
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: vignesh raaj s
RegisterNumber:23005346 
def max_marks(list1):
    for i in list1:
        if i>94:
            return i
```

## Output:
![Screenshot 2023-11-29 222129](https://github.com/vigneshraaj00/FindMaximum/assets/138849113/c8f5b7f4-1583-4cbc-b0e6-817ba9decf52)
![Screenshot 2023-11-29 222434](https://github.com/vigneshraaj00/FindMaximum/assets/138849113/084d1b3c-c9b7-494e-bdbd-ba23988c5df4)
![Screenshot 2023-11-29 222531](https://github.com/vigneshraaj00/FindMaximum/assets/138849113/862ad0ac-af20-4755-b51d-dc6c265d1b62)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
