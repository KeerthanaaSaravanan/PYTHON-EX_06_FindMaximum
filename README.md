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

''' 
Program to mark the maximum of marks using the list method sort
Developed by: Keerthana S
RegisterNumber: 23013398
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Keerthana S
RegisterNumber: 23013398
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Keerthana S
RegisterNumber: 23013398
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![image](https://github.com/KeerthanaaSaravanan/PYTHON-EX_06_FindMaximum/assets/145742596/54c9d584-c0a4-4eb3-b718-f3065ae749d2)
![image](https://github.com/KeerthanaaSaravanan/PYTHON-EX_06_FindMaximum/assets/145742596/97a8c5a1-e00c-4f19-9559-7086b94cfd20)


## Output:
![Screenshot 2023-12-17 174104](https://github.com/KeerthanaaSaravanan/PYTHON-EX_06_FindMaximum/assets/145742596/37f2e6da-d5f6-43c3-b4a3-d6355b7da747)
![Screenshot 2023-12-17 174114](https://github.com/KeerthanaaSaravanan/PYTHON-EX_06_FindMaximum/assets/145742596/8b4d1e81-4470-4f8c-b057-b8be91954c56)
![Screenshot 2023-12-17 174121](https://github.com/KeerthanaaSaravanan/PYTHON-EX_06_FindMaximum/assets/145742596/cfa310cf-0dc3-47ee-894a-812dd18b39ca)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
