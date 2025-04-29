# Regex in Python: To find the sequences of one upper case letter followed by lower case letters
## 🎯 Aim
To write a Python program to find and check if a string contains a sequence of one uppercase letter followed by one or more lowercase letters using regular expressions.
## 🧠 Algorithm
1.Start the program.

2.Import the re module (for using regular expressions).

3.Prompt the user to enter a string.

4.Define a regex pattern: [A-Z][a-z]+

5.[A-Z] matches a single uppercase letter.

6.[a-z]+ matches one or more lowercase letters after it.

7.Use re.search() to search for the pattern in the input string.

8.If a match is found:

9.Print "Found a match!"

Else:

10.Print "No match found."

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
![image](https://github.com/user-attachments/assets/80a3506d-b4c5-4bb5-945e-32a10a5b1b08)

## Result :
The program successfully detects the pattern of one uppercase letter followed by lowercase letters in the input string and prints the appropriate message.
