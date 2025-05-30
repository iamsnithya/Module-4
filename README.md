# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
~~~
class cse:
    def __init__(self,area):
        area=3.1416*r*r
        self.area=area
    def mech(self):
        print("Area of circle:",round(self.area,2))
r=eval(input())
boo=cse(r)
boo.mech()
~~~

## Output
![image](https://github.com/user-attachments/assets/7b885c4d-5239-4bb4-837f-9e06b8168ab0)


## Result
Thus the program executed successfully.


# Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
~~~
Developed by: NITHYA S
Register Number: 212224240106

dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}
dict1.update(dict2)
print(dict1)
~~~

## Output
![image](https://github.com/user-attachments/assets/af699f81-fae8-404e-bf42-0c5eeb8e9080)


## Result
Thus the program executed successfully.


# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
~~~
Developed by: NITHYA S
Register Number: 212224240106
def dictionairy():  
 key_value ={}   
 key_value[2] = 56      
 key_value[1] = 2
 key_value[5] = 12
 key_value[4] = 24
 key_value[6] = 18     
 key_value[3] = 323
 s=sorted(key_value.items(),key=lambda x:x[1])
 print ("Keys and Values sorted in alphabetical order by the value")
 print(s)
  
dictionairy()
~~~

## Sample Output
![image](https://github.com/user-attachments/assets/edeac2b5-f270-4119-98b6-b1d34884cb10)


## Result
Thus the program executed successfully.


# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
~~~
n=int(input())
a=[]
for i in range(n):
    l=int(input())
    a.append(l)

print(a)
try:
    print(a[6])
except Indexerror:
    print("6 is not accepted")
~~~

## Output
![image](https://github.com/user-attachments/assets/15cc653e-bf82-4b19-8e46-e03879c3e6cc)


## Result
Thus the program executed successfully.

# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
~~~
count = 0

try:
    with open('story.txt', 'r') as file:
        for line in file:
            if not line.strip().startswith('T'):
                count += 1
    print(count)
except FileNotFoundError:
    print("The file 'story.txt' was not found.")
~~~
## Output
![image](https://github.com/user-attachments/assets/67e5c069-531c-49bc-8be0-8e8ee4b1d39f)

## Result
Thus the program executed successfully.
