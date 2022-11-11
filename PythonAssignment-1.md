## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
We call python a genral perpose language because we can use python for multiple purposes from web designing, 
building software, machine learning and deep learning softwares etc.
And its called a high-level programming language because it easy for human understanding ie it is closer to human 
language and farther than machine language. 

Q2. Why is Python called a dynamically typed language?
Because when-ever we assign a value to a variable it(python) dynamically assigns the apporpriate data type for it 

Q3. List some pros and cons of Python programming language?
Pros 
1 easy to understand and learn
2 strong developer support 
3 rich library support to write very difficult programs in simple 4-5 lines etc.
Cons
1 it is slow compared to c/c++ so it might be difficult to use on the end devices if there is a very low latency requirement.


Q4. In what all domains can we use Python?
1 Web Development
2 Artificial intelligence ML/DL
3 software development
4 big data 
5 robotics etc.


Q5. What are variable and how can we declare them?
variable is name given to a memory location 
a = 5   here a is a variable name given to a memory location which stores an integer whose value is 5

Q6. How can we take an input from the user in Python?
input_var = input("Enter any value")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
String

Q8. What is type casting?
So the default datatype of the value that has been taken as an input using input() function is string 
so to perform operation on it or lets say we are making an calculator app in python but the user input 
is a string so to persform operations on the input values we have to change its type to we type cast it to int 
so like 
val_1 = int(input("input first val"))
val_2 = int(input("input second val"))
and perforn numerical opration on it now.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Yes 
num_1,num_2,operation_num = list(map(int,input().split(" ")))

Q10. What are keywords?
Keywords are special variables who have some special functionality assigned to it .

Q11. Can we use keywords as a variable? Support your answer with reason
No we cannot use keywords as a variable name as it will create an ambiguity for the intepreter as to which it the variable and which one is the keyword .
So we should not use keywords as vaariables.

Q12. What is indentation? What's the use of indentaion in Python?
So in other languagel like c/c++ we have to use brackets to define the score or range of that function or that block of code 
in python instead of using brakets we use indentation .
We can still use brackets but the indentation is more intutive for humans .

Q13. How can we throw some output in Python?
Using print("") statement

Q14. What are operators in Python?
operators are nothing but symbols who have some meaning assigned to it so say "+" operator has the addition operation assiged to it etc.

Q15. What is difference between / and // operators?
so / float division and // is integer division ie 5/2 = 2.5 and 5//2 is 2

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

print("iNeuron"*4)
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
num = int(input())
if(num%2==0):
  print("even number")
else:
  print("odd number")

Q18. What are boolean operator?


Q19. What will the output of the following?
```
1 or 0
1
0 and 0
0
True and False and True
False
1 or 0 or 0
1
```

Q20. What are conditional statements in Python?
conditional statement in python is a statement which allows to execute one block of code or another block of code based on a condition

Q21. What is use of 'if', 'elif' and 'else' keywords?
if-else statements are used to perform some opetation if a certain condition is satisfied 

num = int(input())
if(num%2==0):
  print("even number")
else:
  print("odd number")
  
elif is used when 


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
