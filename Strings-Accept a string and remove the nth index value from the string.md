 ## List-To create a list with even numbers upto N.

## 🎯 Aim
To write a Python function that accepts an integer N and generates a list of even numbers up to (but not including) N.

## 🧠 Algorithm
1.Start the program.

2.Define a function createlist(N) that takes one parameter N.

3.Use a for loop with range(2, N, 2) to generate even numbers starting from 2 up to (but not including) N.

4.Store the even numbers in a list.

5.Print the list of even numbers.

6.End the program.

## 💻 Program :
```.py
def createlist(num):
    list1=[]
    for i in range(2,num,2):
        list1.append(i)
    print(list1)
```


## Output :
![image](https://github.com/user-attachments/assets/55ffee58-98dd-4076-baf9-9c1f9ad6a4a5)

## Result :
The program successfully generates and prints a list of even numbers less than the given number N.
