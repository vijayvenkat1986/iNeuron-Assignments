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
    
Q26. What is a string? How can we declare string in Python?

A string is a sequence of characters
var_name = 'nandha'

Q27. How can we access the string using its index?
var_name = "nandha"
print(var_name[0])

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
print(string[9:16])
desired_output = "iNeuron"

Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
temp_string = string[-7: ]
new_string = temp_string[::-1]
print(new_string)
desired_output = "norueNi"

Q30. Resverse the string given in the above question.

string = "Big Data iNeuron"
temp_string = string[:16]
new_string = temp_string[::-1]
print(new_string)

Q31. How can you delete entire string at once?

 we can use del keyword to delete the entire string 

Q32. What is escape sequence?

They are primarily used to put nonprintable characters in character and string literals. 
For example, you can use escape sequences to put such characters as tab, carriage return, and backspace into an output stream.

Q33. How can you print the below string?

print("iNeuron's Big Data Course")
or
print('iNeuron\'s Big Data Course')

Q34. What is a list in Python?

A list is a mutable, unordered,heterogenous collection of data 

Q35. How can you create a list in Python?

new_list = []

Q36. How can we access the elements in a list?

We can access an element in a list using its index

Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst[4][2])

Q38. Take a list as an input from the user and find the length of the list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(len(lst))

Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]
lst.insert(2,"Big")
print(lst)

Q40. What is a tuple? How is it different from list?

A tuple is a collection which is ordered and unchangeable.
Tuples are written with round brackets.
Tuples are immutable

Q41. How can you create a tuple in Python?

new_typle = ()

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

tpl = ("nandha","balaji","ganesh")
tpl[3] = "yash"

no its not possible to add a new item in a tuple because it is unchangable .

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

no tuple cannot be appended because tuple are immutable 

Q44. Take a tuple as an input and print the count of elements in it.

value = input("Enter th values")
lst = []
for items in value.split():
    lst.append(items)
print('the tuple is ',tuple(lst),'and the length is',len(tuple(lst)))

Q45. What are sets in Python?

Sets are used to store multiple items in a single variable.
Set is one of 4 built-in data types in Python used to store collections of data
A set is a collection which is unordered, unchangeable, and unindexed.

Q46. How can you create a set?

my_set = {1,34,55,"nandha"}

Q47. Create a set and add "iNeuron" in your set.

my_set = {1,34,55,"nandha"}
my_set.add("ineuron")
print(my_set)

Q48. Try to add multiple values using add() function.

we cannot add multiple values using add()

Q49. How is update() different from add()?

As add() function add a single element to the set, whereas 
update() function iterates over the given sequences and adds them to the set.

Q50. What is clear() in sets?

It removes all the elements from the set

Q51. What is frozen set?

Python frozenset() Method creates an immutable Set object from an iterable. It is a built-in Python function. 
As it is a set object therefore we cannot have duplicate values in the frozenset.

Q52. How is frozen set different from set?

Frozen set is just an immutable version of a Python set object. 
While elements of a set can be modified at any time, elements of the frozen set remain the same after creation.

Q53. What is union() in sets? Explain via code.

Union() Method returns a new set which contains all the items from the original set.
A = {2, 4, 5, 6}
B = {4, 6, 7, 8}
print("A U B:", A.union(B))

Q54. What is intersection() in sets? Explain via code.

Python set intersection() method returns a new set with an element that is common to all set

s1 = {1, 2, 3}
s2 = {2, 3}
print(s1.intersection(s2))

Q55. What is dictionary in Python?

Dictionaries are used to store data values in key:value pairs.
A dictionary is a collection which is ordered*, changeable and do not allow duplicates.

Q56. How is dictionary different from all other data structures.

dictionary stores data in key-value pairs.

Q57. How can we delare a dictionary in Python?

my_dict = {"name":"nandha","Age":22,"location":"TN"}

Q58. What will the output of the following?

var = {}
print(type(var))

it will print dict type

Q59. How can we add an element in a dictionary?

my_dict = {"name":"nandha","Age":22,"location":"TN"}
my_dict["Role"] =  "employee"

Q60. Create a dictionary and access all the values in that dictionary.

my_dict = {"name":"nandha","Age":22,"location":"TN"}
for key,value in my_dict.items():
    print(f"key : {key} and value :{value}")
    
Q61. Create a nested dictionary and access all the element in the inner dictionary.

my_dict = {"name":"nandha","Age":22,"location":"TN","my_dict2":{"name":"balaji","Age":22,"location":"TN"}}
for key,value in my_dict["my_dict2"].items():
    print(f"key : {key} and value :{value}")

Q62. What is the use of get() function?

get() function returns the value of the specified key

Q63. What is the use of items() function?

items() function returns a list containing a tuple for each key value pair

Q64. What is the use of pop() function?

pop() function removes the element with the specified key

Q65. What is the use of popitems() function?

popitems() function removes the last key:value pair from the dictionary

Q66. What is the use of keys() function?

keys() function is used to return a list containing the dictionary's keys

Q67. What is the use of values() function?

keys() function is used to return a list containing the dictionary's values

values() function

Q68. What are loops in Python?

loops are conditional statement which is used to execute a statement a given number of times
 
Q69. How many type of loop are there in Python?

for loop and while loop

Q70. What is the difference between for and while loops?

The for loop is used when we know the number of iterations, that is, how many times a statement must be executed. 
That is why, when we initialize the for loop, we must define the ending point.
A while loop is used when the number of iterations is unknown.

Q71. What is the use of continue statement?

The continue keyword is used to end the current iteration in a for loop (or a while loop),
and continues to the next iteration.

Q72. What is the use of break statement?

'Break' in Python is a loop control statement. It is used to control the sequence of the loop.
Suppose you want to terminate a loop and skip to the next code after the loop; break will help you do that.

Q73. What is the use of pass statement?

The pass statement is used as a placeholder for future code. When the pass statement is executed,
nothing happens, but you avoid getting an error when empty code is not allowed.

Q74. What is the use of range() function?

The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default),
and stops before a specified number.

Q75. How can you loop over a dictionary?

we can loop over a dictionary using for loop

Coding problems

Q76. Write a Python program to find the factorial of a given number.

def factorial(num):
    fact = 1
    for i in range(1,num+1):
        fact = fact * i
    print("the factorial of the given mumber",num,"is : ",fact)
factorial(10)


Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100

def simpleint():
    principle = int(input("Enter your principle : "))
    roi = float(input("Enter the rate of interest : "))
    timeperiod = int(input("Enter your tenure : "))
    SI = (principle*roi*timeperiod)/100
    print(f"the simple inerest is : {SI}")
simpleint()

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

def compoundint():
    principle = int(input("Enter your principle : "))
    roi = float(input("Enter the rate of interest : "))
    time = int(input("Enter your tenure : "))
    A = principle*(1+ (roi/100))**time
    print(f"the simple interest is : {A}")
compoundint()

Q79. Write a Python program to check if a number is prime or not.

num = int(input("Enter the number : "))
if num < 1:
    print("the entered num is not prime")
else:
    for i in range(2,num):
        if (num % i) == 0:
            print("the entered number ",num,"is not prime")        
            break
    else:
         print("The num ",num,"is prime") 
            

Q80. Write a Python program to check Armstrong Number.

num = int(input("Enter a number : "))
power = len(str(num))
temp = num
sum = 0
while temp > 0:
    digit = temp % 10
    sum += digit ** power
    temp = temp // 10 
    
if sum == num :
    print("the entered number is an amstrong number:")
else:
    print("the entered number is not an amstrong number:")

Q81. Write a Python program to find the n-th Fibonacci Number.

def fibonacci(num):
    first = 0
    second = 1
    if num <= 1:
        print ("the nth fibonacci number is  ",num)
    else:
        print ("the nth fibonacci number is  ",first)
        print ("the nth fibonacci number is  ",second)
        for i in range(2,num):
            sum = first + second
            print("the nth fibonacci number is  ",sum)
            first,second = second,sum
       
        
fibonacci(10)

Q82. Write a Python program to interchange the first and last element in a list.

lst = [1,2,3,4,5,6,7,8]
lst[0],lst[-1] = lst[-1],lst[0]
print(lst)

Q83. Write a Python program to swap two elements in a list.

lst = [1,2,3,4,5,6,7,8]
lst[0],lst[-1] = lst[-1],lst[0]
print(lst)

Q84. Write a Python program to find N largest element from a list.

l = [1000,298,3579,100,200,-45,900]
n = int(input("Enter a number:"))
l.sort()
print(l[-n:])

Q85. Write a Python program to find cumulative sum of a list.

list=[10,20,30,40,50]
new_list=[]
j=0
for i in range(0,len(list)):
    j+=list[i]
    new_list.append(j)
     
print(new_list)

Q86. Write a Python program to check if a string is palindrome or not.

strn = input("enter a string :")
rev_str = str( ::-1)
if strn == rev_str :
    print("the given string is palindrome")
else:
    print("the given string is not palindrome")
