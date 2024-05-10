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
```
Developed by: T. Gayathri
Reg No: 212223100007
```

i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(scores):
    scores.sort() 
    return scores[-1]
print(max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])) 
```
ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(nums):
    return max(nums)
print(max_marks([80, 60, 70, 90, 98, 65, 50, 89, 75, 85]))
```
iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(scores):
    max_score = scores[0]  
    for x in scores:
        if x > max_score:
            max_score = x
    return max_score
print(max_marks([81, 63, 74, 92, 100, 66, 50, 89, 75, 87]))
```
## Output:
![image](https://github.com/gayumee/FindMaximum/assets/149037327/dd5762bd-f09e-431f-8ca2-8ddf4705628a)

![image](https://github.com/gayumee/FindMaximum/assets/149037327/9b17fcbd-2b77-4e27-bc9e-3e22570f5beb)

![image](https://github.com/gayumee/FindMaximum/assets/149037327/da6dafb4-1263-4b7c-b04a-41e170fe7468)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
