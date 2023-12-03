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
Developed by: Abbu Rehan
RegisterNumber: 23010259

def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: Abbu Rehan
RegisterNumber: 23010259

def max_marks(marks):
    # write your code here
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: Abbu Rehan
RegisterNumber: 23010259

def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max       


```
## Sample Input and Output

![image](https://github.com/Abburehan/FindMaximum/assets/138849336/e957c6e8-1c64-4b14-855c-d11ce6bc0bf4)
![image](https://github.com/Abburehan/FindMaximum/assets/138849336/e57442a4-44e2-49d6-911b-77f3d7c2b0a0)
![image](https://github.com/Abburehan/FindMaximum/assets/138849336/d6dc39db-d399-41f0-b006-faedaa965a0b)

## Output:

![image](https://github.com/Abburehan/FindMaximum/assets/138849336/0cf58b9e-f481-4901-906a-fba21a8243f9)
![image](https://github.com/Abburehan/FindMaximum/assets/138849336/1c7434bc-6a37-4c5c-a4b5-85d0ad2b683d)
![image](https://github.com/Abburehan/FindMaximum/assets/138849336/2ec9771d-6510-4d78-a6e5-fd9e55238ab8)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
