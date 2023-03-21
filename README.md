# python-Assignment-1
## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans:Python becomes the solution in many domains from web applications, data analysis, data science, machine learning, and Artificial intelligance.python is a high level programming because that can create all types of programs, programers are easily understand  and humn readable elements thats why called as a high level programming and easily interpreted.it is general purpose language beacuse it can be used to create a variety of different programs and isnt specialized for any specific problems.

Q2. Why is Python called a dynamically typed language?
Ans: python doesn’t know about the type of the variable until the code is run.and dynamically typed means it automatically assigns data type while execution of a program.

Q3. List some pros and cons of Python programming language?
pros:
it is a general purpose programming language,high level programing,easily interpreted.
Smooth learning curve
Python is extremely beginner-friendly and relatively easy to learn.
good coding practices rather than on the intricacies of the language structure.
Portability and extensibility to other languages that means write once run anywhere.
it is a open source programing that means free installation at free of cost.

cons:
speed of execution is less compared to any other languages.it has no multi threading because ensures thread safety,
enhances the performance of single-threaded programs and simplifies the integration of non-thread-safe C libraries with Python.
high memory consumption needed.While Python has a garbage collector to manage memory, it doesn’t return resources to the system immediately after the object becomes unnecessary.Python programs tend to run out of memory.

Q4. In what all domains can we use Python?
Ans:Data science,automation,artificial intelligance,machine learning,application development,audio and video applications,desktop GUI,etc.,

Q5. What are variable and how can we declare them?
Ans:A Python variable is a name given to a memory location, and it stores the value.we does not need to give a type of a variables because python interpreter assigns a variable to it.
Declaration:
a="vijaya"
print(a)

Q6. How can we take an input from the user in Python?
Ans:The input() function can be used for take input from user.input() function returns the value entered by the user as a string by default, After taking input, the input() method returns the value entered by the user as a string.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans:default data value is string.even if we enter a interger the input method accepts as a string.


Q8. What is type casting?
Ans:Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans:Yes, multiple input with a single line in Python We can use it in a single statement.To take multiple inputs from the user from the same input line, you can ask the user to seperate the input with a comma or a white space.
eg:a,b=input(),input()
   print(a)
   print(b)

Q10. What are keywords?
Ans:Keywords in python are reserved words that have special meaning.They are generally used to define type of variables. Keywords cannot be used for variable or function names.like And,or,Not,If,Elif,Else,For,While,Break,As.etc.,

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans:No,we cant use keyword as a variable because keywords are reserved words which means it has unique functionality. if we use as a variable then compiler shows as a error.

Q12. What is indentation? What's the use of indentaion in Python?
Ans:indentation means specify a block of code,the use of indentation is without properly indenting the Python code, you will end up seeing IndentationError and the code will not get compiled. Python indentation refers to adding white space before a statement to a particular block of code.

Q13. How can we throw some output in Python?
Ans:With help of printf() function we see the output after execution of a program.
eg:a=2
   b=3
   printf(a+b)
   output:5

Q14. What are operators in Python?
Ans:Operators are special functions,Operators are special symbols that perform operations on variables and values.
Arithmetic operators    +,-,*,/.....
Assignment Operators    =,+=,!=....
Comparison Operators    <,>,>=,<=....
Logical Operators       AND,OR,NOT....
Bitwise Operators       &,^,<<,>>....
Special Operators       is,isnot.

Q15. What is difference between / and // operators?
Ans:you can use both // and / to divide numbers. // means floor division, and / means floating point division.
floor division gives decimals at last,and floationg division does not gives decimals.

Q16. Write a code that gives following as an output.
iNeuroniNeuroniNeuroniNeuron

Ans:a= "iNeuron"
print(a*3)


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans:n= int(input("Enter a number: "))
    if (n% 2) == 0:
      print("even number")
    else:
      print("odd number")

Q18. What are boolean operator?
Ans:Boolean operators that return a boolean value of True or False only.
eg:a = 30
   b = 45
   if(a > 30 and b == 45):
    print("True")
   else:
   print("False")

Q19. What will the output of the following?
```
1 or 0
1
0 and 0
0
True and False and True
False
1 or 0 or 0
```
1
Q20. What are conditional statements in Python?
Ans:if ,if else.
if is used for a satify a condition and prints the output.if-else is used for if condition is true if block of code executes,otherwise else block of code executes.

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans:.if-else is used for if condition is true if block of code executes,otherwise else block of code executes,elif is used of another condition of execute of block of code.
a=18
if(a>18):
print("major")
elif(a>16):
print("kid")
else:
print("minor")
  
  output:"major"

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans:
a=18
if(a>=18):
print("I can vote")
else:
print("I cant vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
Ans:numbers = [12, 75, 150, 180, 145, 525, 50]
numbers1 = []
temp = 0 
for i in numbers:
if i%2==0:
numbers1.append(i)
for i in numbers1:
temp = temp + i
```
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans:a =input(int("enter a no:"))
    b=input(int("enter a no:"))
    c=input(int("enter a no:"))
    if(a>b and b>c):
    print("a is bigger")
    elif(b>cand c>a):
    print("b is bigger")
    else:
    print(:c is bigger")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans:numbers = [12, 75, 150, 180, 145, 525, 50] 
numbers1 = [] 
for i in numbers: 
  if i%5==0: 
    numbers1.append(i) 
    if i>150:  
    numbers1.remove(i) 
    if i>500:
     break
