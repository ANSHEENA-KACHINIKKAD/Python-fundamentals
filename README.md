# Python-fundamentals
## Basic tasks using python fundamentals.

Python Fundamentals Exercises

This repository contains Python code solutions for various fundamental exercises.

## Exercise 1: Printing Personal Information
* **Description:** Prints your name, student number, and email address.
*  code:

         input("Enter your name:")
   
         input("Enter your student number:")
  
         input("Enter email address:")

  

## Exercise 2: Printing with Escape Sequences
* **Description:** Prints information using escape sequences for formatting.
* code:

         input("Enter your name:")
  
         input("\n Enter your student number:" )
  
         input("\n Enter email address:")

## Exercise 3: Arithmetic Operations
* **Description:** Performs basic arithmetic operations on two numbers.
* code:

          a=14
          b=7
  
          print(a,"+",b,"=",a+b)
  
          print(a,"-",b,"=",a-b)
  
          print(a,"*",b,"=",a*b)
  
          print(a,"/",b,"=",a/b)
  
          print(a,"//",b,"=",a//b)

## Exercise 4: Printing Numbers 
* **Description:** Displays the numbers from 1 to 5 as steps.
* code:

      for i in range(1,6):
  
         print(i)

## Exercise 5: Multiline String Output
* **Description:** Prints a multiline string with quotation marks and line breaks.
* code:

      print('"SDK" stands for"Software Development Kit",\n whereas \n"IDE" stands for"Integrated Development Environment".')


## Exercise 6: String Formatting with Escape Sequences
* **Description:** Demonstrates various string formatting techniques using escape sequences.
* code:

         print("python is an \"awesome\"language.")
  
         print("python\n\t2023")
  
         print('I\'m from Entri.\b')
  
         print("\65")
  
         print("\x65")
  
         print("Entri","2023",sep="\n")
  
         print("Entri","2023",sep="\b")
  
         print("Entri","2023",sep="*",end="\b\b\b\b")

## Exercise 7: Variable Types and Conversions
* **Description:** Defines variables of different types and calculates their sum.
*  code:

          num=23
   
          textnum="57"
   
          decimal=98.3
   
          print(type(num))
   
          print(type(textnum))
   
          print(type(decimal))
   
          sum=num+int(textnum)+decimal
   
          print(type(sum))

## Exercise 8: Time Calculations
* **Description:** Calculates the number of minutes in a year using variable assignments.
* code:

         days_in_year=365
  
         min_un_hr=60
  
         hr_in_day=24
  
         min_in_year=min_un_hr*hr_in_day*days_in_year
  
         print(min_in_year)

## Exercise 9: User Input and Greeting
* **Description:** Asks the user for their name and prints a greeting.
* code:

         name=(input("Enter your name:"))
  
         print(f"Hi {name},welcome to Python programming ")

## Exercise 10: Currency Conversion
* **Description:** Converts pounds to dollars.
* code:

      // create python file named PoundsToDollars.py
  
      pounds=int(input("Enter amounts in pounds:"))
  
      print(f"the given {pounds} pounds is ",pounds*1.30,"Dollars ")


## Note
This repository contains Python code solutions for foundational exercises, covering:

Basic Input/Output: Printing text, using escape sequences.
Arithmetic Operations: Performing calculations.
Control Flow: Using loops and conditional statements.
String Manipulation: Working with text strings.
Variable Types and Conversions: Understanding data types and conversions.
Time Calculations: Performing calculations involving time units.
User Input and Output: Interacting with the user.
Currency Conversion: Converting one currency to another.
3. Run the Python script using your preferred Python environment.


