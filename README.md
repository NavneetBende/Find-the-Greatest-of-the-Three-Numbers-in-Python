# Find-the-Greatest-of-the-Three-Numbers-in-Python

Find the Greatest of the Three Numbers​ in Python
Find the Greatest of the Three Numbers
Given three integer inputs the objective is to find the largest among them. Therefore we write a code to Find the Greatest of the Three Numbers in Python.

Example
Input : 20 30 10
Output : 30
Largest Number Among Three Numbers in Python
Find the Greatest of the Three Numbers in Python Language
Given three integers as inputs the objective is to find the greatest among them. In order to do so we check and compare the three integer inputs with each other and which ever is the greatest we print that number. Here are some methods to solve the above problem.

Method 1: Using if-else Statements
Method 2: Using Nested if-else Statements
Method 3: Using Ternary Operator
We’ll discuss the above mentioned methods in-depth in the upcoming sections.


Method 1: Using if-else Statements
In this method we use if-else statements to find the Largest Number among the three integer inputs.

Working
For integer inputs number1, number2 and number3

Initialize the required variables.
Using if-else check if the numbers are greater than max and change max if true.
Print max variable.
Let’s implement the working in Python Language.

Python Code
Run
num1, num2, num3 = 10 , 30 , 20
max = 0
if num1 >= num2 and num1 >= num3:
  print(num1)
elif num2 >= num1 and num2 >= num3:
  print(num2)
else:
  print(num3)
Output
30
Method 2: Using Nested if-else Statements
In this method we use if-else statements within one another to find the Largest Number among the three integer inputs.

Working
For integer inputs number1, number2 and number3

Initialize the required variables.
Using nested if-else check if the numbers are greater than max and change max if true.
Print max variable.
Let’s implement the working in Python Language.

Python Code
Run
num1, num2, num3 = 10 , 350 , 550
max = 0
if num1 >= num2:
    if num1 >= num3:
        print(num1)
elif num2 >= num1:
    if num2 >= num3:
        print(num2)
    else :
        print(num3)
Output
30
Method 3: Using Ternary Operator
In this method we use Ternary operator to compare and find the Largest Number among the three integer inputs.

Working
For integer inputs number1, number2 and number3

Initialize the required variables.
Using Ternary Operator check if the numbers are greater than max and change max if true.
Print max variable.
Let’s implement the working in Python Language.

Python Code
Run
num1, num2, num3 = 10 , 30 , 20
max = num1 if num1>num2 else num2
max = num3 if num3>max else max
print(max)
Output
30
