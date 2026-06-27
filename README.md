<img width="1310" height="803" alt="image" src="https://github.com/user-attachments/assets/8dc3ffb0-17a4-4fdb-94c4-6806870f6440" /># Find the maximum of a list of numbers
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
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    max_val = marks[0]
    
    for i in marks:
        if i > max_val:
            max_val = i
    
    return max_val
```
## Output:

i)	# To find the maximum of marks using the list method sort.
<img width="1307" height="810" alt="Screenshot 2026-06-27 133403" src="https://github.com/user-attachments/assets/ed0f6958-db14-4549-b5b5-c5463a489948" />

ii)	# To find the maximum marks using the list method max().
<img width="1310" height="803" alt="Screenshot 2026-06-27 133452" src="https://github.com/user-attachments/assets/bda519cf-da86-48e7-9ca3-2e2522c5d490" />

iii) # To find the maximum marks without using builtin functions.
<img width="1312" height="802" alt="Screenshot 2026-06-27 133700" src="https://github.com/user-attachments/assets/ab78f96b-94fd-438e-b9aa-4c238183f299" />

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
