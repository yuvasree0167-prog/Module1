# Conditional Statements in Python: Even or Odd Checker

## Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## Program
```
a=int(input())
if(a%2==0):
    print("EVEN")
else:
    print("ODD")
```
## Output
<img width="452" height="253" alt="image" src="https://github.com/user-attachments/assets/fb8b3a20-4476-4110-97ee-53ecba6371a5" />

## Result
Thus,the Python program to check whether the given number is even or odd using if...else statements is created successfully.

# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## Program
```
a = (False == True)
b = (False== 0)
c = False + True
d = False + 5
print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
```

## Output
<img width="436" height="301" alt="image" src="https://github.com/user-attachments/assets/f2c04c93-aa47-4913-818f-435ca90b791c" />

## Result
Thus,the Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False is created successfully.
# Datatypes-Character Literal in Python

## Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## Program
```
a='T'
b='a'
print(a)
print(b)
```
## Output
<img width="396" height="238" alt="image" src="https://github.com/user-attachments/assets/72b9ef07-c287-4c9a-b6a3-a1cb79e244ed" />

## Result
Thus,the Python program that prints the characters 'T' and 'a' using character literals is created successfully.
# Datatypes-Complex Number Creation in Python

## Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## Program
```
a=int(input())
b=int(input())
x=complex(a,b)
print(x)
print(x.real)
print(x.imag)
```

## Output
<img width="472" height="385" alt="image" src="https://github.com/user-attachments/assets/331a4787-dbbe-472c-a092-9e7a8c8d7f54" />

## Result
Thus,the Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts is created successfully.
# Datatypes-Read and Print a String in Python

## Aim
To write a Python program to read a string from the user and then print it.

## Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## Program
```
men_stepped_on_the_moon=input()
print(men_stepped_on_the_moon)
```
## Output
<img width="707" height="187" alt="image" src="https://github.com/user-attachments/assets/c424804f-bf0f-49bf-ac2f-58b3b0b3f2ae" />

## Result
Thus,the Python program to read a string from the user and then print it is created successfully.
