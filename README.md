# Python-Programming-Week-11
1.Write a Python program that asks the user for their age and prints a message based on the age. Ensure that the program handles cases where the input is not a valid integer.



Input Format:

A single line input representing the user's age.



Output Format:

Print a message based on the age or an error if the input is invalid.

CODE:


try:
    n=int(input())
    
    if n<0:
        print("Error: Please enter a valid age.")
    else:
        print(f"You are {n} years old.")
except ValueError:

    print("Error: Please enter a valid age.")
    
except EOFError:

    print("Error: Please enter a valid age.")
    
  #2.Develop a Python program that safely performs division between two numbers provided by the user. Handle exceptions like division by zero and non-numeric inputs.

Input Format: Two lines of input, each containing a number.

Output Format: Print the result of the division or an error message if an exception occurs.

CODE:

try:

    m=input()
    n=input()
    a=float(m)
    b=float(n)
    g=a%b
    print(a/b)
    
except ZeroDivisionError:

    print("Error: Cannot divide or modulo by zero.")
    
except ValueError:

    print("Error: Non-numeric input provided.")
    
except EOFError:

    print("Error: Cannot divide or modulo by zero")
    
 #3.Write a Python program that asks the user for their age and prints a message based on the age. Ensure that the program handles cases where the input is not a valid integer.

Input Format: A single line input representing the user's age.

Output Format: Print a message based on the age or an error if the input is invalid.

CODE:

try:

    n=int(input())
    
    if n<0:
    
        print("Error: Please enter a valid age.")
        
    else:
    
        print(f"You are {n} years old.")
        
except ValueError:

    print("Error: Please enter a valid age.")
    
except EOFError:

    print("Error: Please enter a valid age.")
    
#4.Write a Python script that asks the user to enter a number within a specified range (e.g., 1 to 100). Handle exceptions for invalid inputs and out-of-range numbers.

Input Format:

User inputs a number.

Output Format:

Confirm the input or print an error message if it's invalid or out of range.

CODE:

try:

    a =int(input())
    
    if 1 <= a <=100:
    
        print("Valid input.")
        
    else:
    
        print("Error: Number out of allowed range")
        
except ValueError:

    print("Error: invalid literal for int()")
    
    #5.Write a Python program that performs division and modulo operations on two numbers provided by the user. Handle division by zero and non-numeric inputs.

Input Format:

Two lines of input, each containing a number.

Output Format:

Print the result of division and modulo operation, or an error message if an exception occurs.

CODE:

try:

    a=int(input())
    
    n=int(input())
    
    if(a%n==0):
    
        print("Division result:",a/n)
       
       print("Modulo result:",a%n)
    elif((a%n)!=0):
    
        print("Division result:",a/n)
        
        print("Modulo result:",a%n)
except ZeroDivisionError:

    print("Error: Cannot divide or modulo by zero.")
    
except ValueError:

    print("Error: Non-numeric input provided.")
    
