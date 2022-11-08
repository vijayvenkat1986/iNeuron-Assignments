## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Python is used in many different fields like web development, artificial intelligence , machine learning and many areas due to which it is called as general purpose programming language.
Also python is a programmer friendly language and user does not need to concentrate on memory management and security due to which it is called high level programming language.

Q2. Why is Python called a dynamically typed language?
No explicit typing of data types which python will automatically pick based on the values provided due to which it is called dynamically types programming language.

Q3. List some pros and cons of Python programming language?
1. Python cannot be used for mobile applications.
2. Performance of python is not much better compared to other programming languages but inspite of it Python has many rich libraries in supporting its performance.

Q4. In what all domains can we use Python?
Python can be used in many domains and not much limitations.

Q5. What are variable and how can we declare them?
Variable name should start with a letter or underscore character(_) and cannot start with a digit

Q6. How can we take an input from the user in Python?
By using input()  function

Q7. What is the default datatype of the value that has been taken as an input using input() function?
String

Q8. What is type casting?
Type casting is convertion of variable from one data type to another and in python there are 2 types of type casting,
1. Implicit Type Convertion
2. Explicit Type Convertion

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Yes. We can take more than 1 input using single input()  function by using split() function.

Q10. What are keywords?
These are special reserved words that have some meaning and purpose and can't be used for anything other than these purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
No. As the reserved words are only for the intended purposes it cannot be used for any other purpose/

Q12. What is indentation? What's the use of indentaion in Python?
Indentation is very important in python and it refers to the space at the beginning of a code line.

Q13. How can we throw some output in Python?
Using print() function.

Q14. What are operators in Python?
Operators are used to perform operations on variables and values.

Q15. What is difference between / and // operators?
/ - Division which provides Decimal values
// - Floor Division which provides integer values as output

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
str1 = "iNeuron"
print('```')
print(str1*3)
print('```')

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
num1 = int(input("Enter the Number:"))
if num1%2==0:
    print("Even")
else:
    print("Odd")

Q18. What are boolean operator?
Boolean operator is used to represent the truth value of an expression.

Q19. What will the output of the following?
```
1 or 0
Ans : 1

0 and 0
Ans : 0

True and False and True
Ans: False

1 or 0 or 0
Ans : 1
```

Q20. What are conditional statements in Python?
Used to handle conditions in the program. It can be if, if-else.

Q21. What is use of 'if', 'elif' and 'else' keywords?
if - if any condition is satisfied
elif - This is Else If if previous condition does not satisfy, need to validate if this gets satisfied.
else - If all other conditions does not satisfy, this will be executed.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
age = int(input("Enter the Age:"))
if age>=18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
numbers1 = []
temp = 0
for i in numbers:
    if i%2==0:
        numbers1.append(i)
for i in numbers1:
    temp = temp + i

print(temp)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
num1,num2,num3 = input("Enter 3 numbers: ").split()
num1 = int(num1)
num2 = int(num2)
num3 = int(num3)
print(num1)
print(num2)
print(num3)
print(max(num1,num2,num3))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
numbers1 = []
for i in numbers:
    if i%5==0:
        numbers1.append(i)
    if i>150:
        numbers1.remove(i)
    if i>500:
        break
        
for i in numbers1:
    print(i)
