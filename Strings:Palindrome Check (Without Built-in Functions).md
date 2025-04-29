# Tuple-The multiples of 9 up to N and the print length of the tuple.

## 🎯 Aim
To write a Python program that creates a tuple of the multiples of 9 up to a given number N (entered by the user), and prints both the tuple and its length.

## 🧠 Algorithm
1.Start the program.

2.Prompt the user to enter a number N.

3.Convert the user input to an integer.

4.Use a for loop with range(9, N, 9) to generate all multiples of 9 less than N.

5.Store the results in a tuple.

6.Print the tuple.

7.Use the len() function to determine the length of the tuple.

8.Print the length of the tuple.

9.End the program.

## 🧾 Program :
```.py
a=int(input())
list1=[]
for i in range(9,a):
    if i%9==0:
        list1.append(i)
print(tuple(list1))
print(f"Length of the tuple is {len(list1)}")
```



## Output :
![image](https://github.com/user-attachments/assets/5f9dd96e-110a-4f36-bd44-e4f08364a6c8)


## Result :
The program successfully creates and displays a tuple containing all multiples of 9 less than the entered number N and prints the correct length of that tuple.
