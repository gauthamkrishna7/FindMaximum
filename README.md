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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: GAUTHAM KRISHNA S
RegisterNumber: 23012450
'''
def max_marks(marks):
    marks.sort()
    max = marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: GAUTHAM KRISHNA S
RegisterNumber: 23012450
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: GAUTHAM KRISHNA S
RegisterNumber: 23012450
'''
def max_marks(list1):
    max = 0
    for i in list1:
        if max<=i:
            max = i
    return max
```

## Output:
<img width="1467" alt="image" src="https://github.com/gauthamkrishna-s/FindMaximum/assets/146015011/44624d8d-0532-453d-932c-5ef9265382ea">
<img width="1467" alt="image" src="https://github.com/gauthamkrishna-s/FindMaximum/assets/146015011/0b7f2ffd-2c8e-4313-bcee-0d53d5e2335d">
<img width="1467" alt="image" src="https://github.com/gauthamkrishna-s/FindMaximum/assets/146015011/017317ae-750e-43c7-8613-3d2cdc881143">




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
