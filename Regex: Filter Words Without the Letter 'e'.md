# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim :
To write a Python program to find sequences where one uppercase letter is followed by one or more lowercase letters in a given string.
## 🧠 Algorithm :
1.Start the program.

2.Import the re module (used for regular expression operations).

3.Define a function to accept a string as input.

4.Create a regular expression pattern: [A-Z][a-z]+

5.[A-Z] matches one uppercase letter.

6.[a-z]+ matches one or more lowercase letters.

7.Use re.search() to check if the pattern exists in the input string.

8.If a match is found, print "Found a match!".

9.If no match is found, print "No match found.".

10.Call the function with a sample input.

11.End the program.


## 🧾 Program :
```.py
import re
text=input()
pattern=re.compile(r"[A-Z]+[a-z]")
matches=pattern.findall(text)
if len(matches)!=0:
    print("Found a match!")
else:
    print("Not matched!")
```
## Output :
![image](https://github.com/user-attachments/assets/d558cfc0-d11d-4aaa-92ef-7baa15f44306)


## Result :
The program successfully identifies that the string "Saveetha" contains a sequence starting with an uppercase letter followed by lowercase letters, and prints "Found a match!".
