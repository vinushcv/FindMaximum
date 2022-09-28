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
#developed by: vinushcv
#registration number:22001897

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large




```

ii)	# To find the maximum marks using the list method max().
```Python
#developed by: vinushcv
#registration number:22001897

    
def max_marks(marks):
    maxi=max(marks)
    return maxi



```

iii) # To find the maximum marks without using builtin functions.
```Python
#developed by: vinushcv
#registration number:22001897
max1=marks[0]
    for i in marks:
        if i>max1:
            max1 = i
    return max1
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![output](max.png)
![output](max.png)
![output](max.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.