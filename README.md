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
Developed by: ISWARYA.P
RegisterNumber: 23013459
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: ISWARYA.P
RegisterNumber: 23013459
'''
def max_marks(marks):
    a=max(marks)
    return a# write your code here


```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: ISWARYA.P
RegisterNumber:23013459 
'''
def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a
```
 
 ## Output:

i)



![Alt text](<method sort.png>)
![Alt text](method-sort-1.png)

ii)


![Alt text](<method max.png>)
![Alt text](method-max-1.png)

iii)


![Alt text](<builtin func.png>)
![Alt text](<method-built in function-1.png>)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.