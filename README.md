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
Program to mark the maximum of marks using the list method sort
Developed by: GANJI MUNI MADHURI
RegisterNumber: 23002365
'''
def max_marks(marks):
    a=sorted(marks)
    b=a[-1]
    return b


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: GANJI MUNI MADHURI
RegisterNumber: 23002365
'''
def max_marks(marks):
    a=max(marks)
    return a


```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: GANJI MUNI MADHURI    
RegisterNumber: 23002365
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        

```
# sample input and output:
![output](/img/max_marks1.jpg)
![output](/img/marks%20(2).png)
![output](/img/Screenshot%202023-11-29%20113735.png)
## Output:
![output](/img/Screenshot%202023-11-29%20115041.png)
![output](/img/Screenshot%202023-11-29%20115104.png)
![output](/img/Screenshot%202023-11-29%20115133.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.