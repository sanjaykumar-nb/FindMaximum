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
# Program Name : FindMaximum
# Name : SANJAYKUMAR N B
# Register Number : 212223230189

```
i)	# To find the maximum of marks using the list method sort.
```
def max_marks(m):
    m.sort()
    high=m[-1]
    return high


```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(m):
    large=max(m)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max




```



## Output:

![Screenshot 2024-03-31 235310](https://github.com/sanjaykumar-nb/FindMaximum/assets/154039979/9ecb75aa-9384-4f0b-9609-2fae21803dfd)

![Screenshot 2024-03-31 235323](https://github.com/sanjaykumar-nb/FindMaximum/assets/154039979/881321d3-2e13-4ee5-a5ed-8e87c0819e5c)

![Screenshot 2024-03-31 235338](https://github.com/sanjaykumar-nb/FindMaximum/assets/154039979/09d614df-23ae-4ff5-b49c-a82ec633d680)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
