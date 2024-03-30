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

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    max_marks=max(marks)
    return max_marks



```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    max= marks[0]
    for i in marks[1:]:
        if i > max:
            max = i
    return max



```



## Output:
![image](https://github.com/Vedha0406/FindMaximum/assets/150884870/41c3bff0-cde0-4bc3-87f2-24031749a279)
![image](https://github.com/Vedha0406/FindMaximum/assets/150884870/73f01308-67d9-4f20-ad82-d48a8a8f1af9)
![image](https://github.com/Vedha0406/FindMaximum/assets/150884870/917ff13a-9425-443e-aec8-470cd9cb90f2)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
