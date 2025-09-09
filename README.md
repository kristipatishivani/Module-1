# Experiment No: 1A Python Basics- Printing Multiline String
# AIM
To create a Python program to print the string in multiple lines using triple quotes.

# ALGORITHM
Begin the program. Use triple quotes (''' or """) to define a string that spans multiple lines. Use the print() function to display the multi-line string. Terminate the program.

# PROGRAM
# Reg No-212222060126
# Name-Kristipati Shivani


print("""I am a string literal
... has more than one
... line
....placed inside triple single quotes
I am a string literal
... has more than one
... line
....placed inside triple double quotes""")
# OUTPUT
<img width="1189" height="462" alt="image" src="https://github.com/user-attachments/assets/2f42e607-8df7-4ea1-93a6-a04ed9d22b11" />

# RESULT
The program prints a multiline string using both triple single (''') and triple double (""") quotes.

# Experiment No: 1B- Data Types – Printing Integer Literals
# AIM
To write a Python program to print the following integer and float literals: 10,3.14

# ALGORITHM
Begin the program. Initialize the integer literals 10. Initialize the float literals 3.14. Use the print() function to display the numbers 10 and 3.14 Terminate the program.

# PROGRAM
# Reg No-21222060126
# Name-Kristipati Shivani

a=int(input())
b=float(input())
print(a,b)

# OUTPUT
<img width="1170" height="310" alt="image" src="https://github.com/user-attachments/assets/8a2c2188-e27a-4dcc-be61-3059dcc01645" />


# RESULT
The program successfully prints the integer and float literals 10,3.14.

# Experiment No: 1C-Varibles and Expressions, Operators - using two values using all the relational operators
# AIM
To write a Python program for two values using all the relational operators (>,<,>=,<=,== ,!=).

# ALGORITHM
Start Assign values a = 13 and b = 33 Compare a and b using > , < , >= , <= , == , != Print the results of each comparison Stop

# PROGRAM
# Reg.No-212223060113
# Name-Kristipati Shivani

a = 13
b = 33
# a > b is False
print(a > b)
# a < b is True
print(a < b)
# a == b is False
print(a == b)
# a != b is True
print(a != b)
# a >= b is False
print(a >= b)
# a <= b is True
print(a <= b)
# OUTPUT
<img width="1196" height="353" alt="image" src="https://github.com/user-attachments/assets/e9247d7b-9677-4e95-aba8-32cef1f01ff9" />

# RESULT
Thus, the Python program for comparing two numbers using all relational operators is successfully executed and the above results are obtained.

# Experiment No: 1D – Conditional Statements- Checking Vowel or not
# AIM
To Write a Python program to check whether the given character is a vowel or not using if..else statement

# ALGORITHM
Begin the program. Take a character input from the user Convert the character to lowercase Check if the lowercase character is one of the vowels: 'a', 'e', 'i', 'o', 'u' If it is a vowel, display "The given character is a vowel" Otherwise, display "The given character is NOT a vowel" Terminate the program.

# PROGRAM
# Reg.No-212222060126
# Name-Kristipati Shivani
num=int(input())
if num % 2==0:
    if num >=25:
        print(num,"is an Even number")
        print(num,"is greater than or equal to 25")
    else:
        print(num,"is an Even number")
        print(num,"is lesser than 25")
else:
   print(num,"is NOT an Even number")
# OUTPUT
<img width="1057" height="327" alt="image" src="https://github.com/user-attachments/assets/5205ed0c-bbe4-4579-9b8e-b56a012a79a5" />

# RESULT
A Python program to check whether the given character is a vowel or not using if..else statement has been implemented and executed successfully.

# Experiment No: 1E – SEB-Minimum of Three Numbers
# AIM
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

# ALGORITHM
Begin the program. Read the three numbers: num1, num2, and num3 from the user. Compare num1, num2, and num3 to find the smallest number: If num1 is less than or equal to both num2 and num3, then num1 is the minimum. Else, if num2 is less than or equal to both num1 and num3, then num2 is the minimum. Otherwise, num3 is the minimum. Print the minimum value along with the input numbers in the format: "The minimum of num1, num2, num3 is min_num." Terminate the program.

# PROGRAM
# Reg.No-212222060126
# Name-Kristipati Shivani
num1 = int(input())
num2 = int(input())
num3 = int(input())
min_num = num1 if (num1 <= num2 and num1 <= num3) else num2 if (num2 <= num1 and num2 <= num3) else num3
print(f"The minimum of {num1}, {num2}, {num3} is {min_num}")
# OUTPUT
<img width="1194" height="417" alt="image" src="https://github.com/user-attachments/assets/22b9af01-6bc4-4126-9f18-de227bb02da3" />

# RESULT
Thus the python program for finding a minimum of three numbers has been implemented and executed successfully.
