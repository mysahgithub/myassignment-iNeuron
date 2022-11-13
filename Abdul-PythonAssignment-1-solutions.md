## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

its written human understand language and Python is an interpreted language. This means that every time a program is run, its interpreter runs through the code and translates it into machine-readable byte code  		

Q2. Why is Python called a dynamically typed language?

because the type of variable is determined during run time..

Q3. List some pros and cons of Python programming language?

pros

its easy to understand
it has minimal code compared to other languages
its indentation make look the code easier
its a run time interpreter language
it has wide range of lib support

cons
its bit slower compared to the compiler based language.


Q4. In what all domains can we use Python?

almost all example... mainly data enggineering,machine learning etc...

Q5. What are variable and how can we declare them?

its a name given to the memory block to identify when it's called of any kind of operation...
declare by a = 10, b=20
here a and b are variables storing the int values in memory

Q6. How can we take an input from the user in Python?

using the keyword input()

Q7. What is the default datatype of the value that has been taken as an input using input() function?

string 

Q8. What is type casting?

converting one data type to other..like int to float or float to int ...using int(float-value) and float(int value)

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

yes, if we can take this into any conditional statements.
no, in other cases.

Q10. What are keywords?

to understand python language need keywords like value,operators,control or conditional,

Q11. Can we use keywords as a variable? Support your answer with reason.

no, we can't use this keyword as variable as these are syntax specfic used for coding

Q12. What is indentation? What's the use of indentaion in Python?

it define the start and end of particaular statements and its a tab space.

Q13. How can we throw some output in Python?

using print() statement.

Q14. What are operators in Python?

these are used to perform the mathematical work and to check the logical operations.

Q15. What is difference between / and // operators?

 / division operator and // is or operator

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

print('iNeuroniNeuroniNeuroniNeuron')

-------or-------
a = 'iNeuroniNeuroniNeuroniNeuron'

print(a);




Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

num =int(input('please enter number :'))

if num%2==0:
    print('given number is even')
else:
    print('given number is odd')

Q18. What are boolean operator?

true
false

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

1 0
0
false
1 0 0

Q20. What are conditional statements in Python?

if,elif,else,while,for,or,and

Q21. What is use of 'if', 'elif' and 'else' keywords?

these are conditional statement used to get at least one output

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

age =int(input('please enter your age :'))

if age>=18:
    print('I can vote')
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers[0 : ]:
    if i%2==0:
        print(i)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

num1 =int(input("please enter the 1st num :" ))
num2 =int(input("please enter the 2nd num :" ))
num3 =int(input("please enter the 3rd num :" ))

if num1>num2 and num1>num3:
    print("the greatest number is :", num1)
elif num2>num1 and num2>num3:
    print("the greatest number is :", num2)
else:
    print("the greatest number is :", num3)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers[0 : ]:
    if i%5==0:
        if i > 150 and i <=500:
            continue
        elif i > 500:
            break
        else:
            print(i)
