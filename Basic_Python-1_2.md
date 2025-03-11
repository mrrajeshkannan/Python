# Basic Python -1

Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

Python is case sensitive programming.

print(100+45)

145

print(9-3234/453)

1.8609271523178812

print('ten10')

ten10

## Print the text

Hello

World !

print('Hello')

print('World !')

## Print the following text in the output:

Hello

World !

print('Hello')

print()

print('World !')

Data Types: -

Python Data Types are used to define the type of a variable. It defines what type of data we are going to store in a variable.

# Data Types: -

| Text(string) Type: | str |
| --- | --- |
| Numeric Types: | int, float, complex |
| Sequence Types: | list, tuple, range |
| Mapping Type: | dictionary |
| Set Types: | set, frozenset |
| Boolean Type: | bool |
| Binary Types: | bytes, bytearray, memoryview |
| None Type: | NoneType |

* Numeric - int,
* Float
* String - str
* Boolean - bool
* None - NoneType
* Set - set, frozenset

## String:-

X= ‘srk’

## Numeric Types:

### Int:-

X=123

X=-123

### Float:-

X=12.45

X=65.877

X=0.234

X=.7365

### Complex :-

x = 1j

X= ‘135srlo’

# bool

True

False

## To check data types :-

>>> i=5.0

>>> j=5

>>> k='srk'

>>> type(i)

<class 'float'>

>>> type(j)

<class 'int'>

>>> type(k)

<class 'str'>

>>>

## Operators:-

If any operator in float the result will be float ex(5-4.0=>1.0)

### Addition:- (+)

10+3 #13

Ans:- 13

### Subtraction:- (-)

10-3 #7

Ans:- 7

### Multiplication:- (\*)

print(10 \*3) #30

Ans:- 30

### Divide:- (/)

10/3 #int / int ---> #float

#Y it is rounded to 5 but it should be 4

Ans:- 3.3333333333333335

Divide operates always give the result as floating values

9/9

## Ans:- 1.0

x = 10

y = 2.5

print(x / y)

Ans:- 4.0

3.5+3.5

A. 7

B. 7.0

C. "7"

B is correct

### Exponential/power operator:- (\*\*)

The exponentiation operator (\*\*) raises the first operand to the power of the second operand:

2\*\*3 => 8 (2\*2\*2)

5\*\*-1 =>0.2

### Floor Division:- (//)

Floor division will give the result as integer. (26//2=>13)

(26//2=>13)

### Modules:- (%)

Only gives the reminder 10%3 => 1

When any one values is negative it change the behavers -10%3=>2

### Presedence of operator:-

BODMAS

And +- is ame & \*/ is same and go with left to right.

### Bool :-

Any number other than 0 is considerd as bool

Bool(1234)=> True

Bool(0.0003)=>True

Bool(raje‘)=>True

Bool(‘ ‘)=>True

Bool(0)+>False

Bool(0.0)=>False

Bool(‘’)=>False

Bool(None)=>False

### Comparison Operator:- will give you True/ False

> Greater then

< Less then

>= Greater then operator

<= Less then operator

== comparision operator

### Logical operator:-

AND

marks>=35 and marks>50

False

OR

gender = 'male'

gender =='male' or gender =="female"

True

amount = int(input("Enter your amount"))

amount%500==0 or amount%200==0

Enter your amount1700

False

NOT

not 24<35

False

## Control Statements:-

The if-elif-else statement is used to conditionally execute a statement or a block of statements. [Conditions](https://www.w3resource.com/python/python-operators.php) can be true or false, execute one thing when the condition is true, something else when the condition is false.

In resume write it I can break complex problem into simple one

Indentation (space is fixed for if statement)

x =10

if x>9 and x<12:

print("Good Morning")

print("dancing")

print("On the chair")

print("Satwik")

Good Morning

dancing

On the chair

Satwik

x =2

if x>9 and x<12:

print("Good Morning")

print("dancing")

print("On the chair")

print("Satwik")

else:

print("It not morning")

It not morning

## If else :-

Question :-

Take a password from the user and match the password:

password ='Donottell'

input\_frm=input('Enter your passwrod: ')

if input\_frm==password:

print('valid')

else:

print('invalid')

Question:

Question-2 ATM Dispatch 500 and 200 Rs notes are available Take amount from user, if amount dischargeable, print("Discharging cash") Else, print("Denomination not available")

amt=int(input('Enter your amount:'))

if amt%500==0 or amt%200==0 or (amt%500)%200==0:

print('Discharging cash')

else:

print('Denomination not available')

## ****Greeting in 24hr format****

time = int(input())

if time > 9 and time <= 12:

print("GM")

else:

if time>12 and time<=17:

print("GA")

else:

if time>17 and time<=24:

print("GN")

else:

print("SOja....!")

### Only if class:- (It is very important)

marks = 56

if marks>=75:

print("1st class")

if marks>=50:

print("2nd class")

if marks>=35:

print("3rd class")

else:

print("Not passed")

2nd class

3rd class

marks = 87

if marks>=75:

print("1st class")

elif marks>=50:

print("2nd class")

elif marks>=35:

print("3rd class")

else:

print("Not passed")

1st class

Take an integer and print if its positive or negative:-

a=int(input('Enter any integer:'))

if a>=0:

print('Your input is positive')

elif a<0:

print('Your input is Negative')

Take a non negative single digit number as input:

If num \*\* 5 % 50 + 20 -6 > 15 then print black or print blue

num=int(input('Enter single digit number:'))

if num<=0 or num>=10:

print('Invalied input')

elif num \*\* 5 % 50 + 20 -6 > 15 :

print('BLACK')

else:

print('Blue')

## Lower & upper function:-

It will convert variable in to lower

lan=input('Enter string:')

if lan.lower():

print('Great Choice!')

else:

print('Think again')

lan=input('Enter string:').upper()

if lan==PYTHON:

print('Great Choice!')

else:

print('Think again')

## .isdigit()

It will give true when the variable is integer otherwise false.

lan=input('Enter number:')

num=lan.isdigit()

if num==True:

print('Great Choice! it is number')

else:

print('Think again')

## .isalpha():-

Is give you true if the variable is alphabet.

feedback=input('Enter your feedback:')

if feedback.isalpha():

print('Thank you for the feed back')

if feedback=='Great' or feedback=='Fantastic' or feedback=='Awesome':

print('Thank you so much !')

else:

print('You are not provided feedback')

Take aninput n if n is multiple of 3 print fizz else n is multiple of 5 print buzz

Multiple of both fizzbuzz

n=int(input('Enter the integer:'))

if n%3==0 and n%5==0:

print('FIZZBUZZ')

elif n%3==0:

print('FIZZ')

elif n%5==0:

print('BUZZ')

Question - Stream Selection Take in three inputs from a user which are marks in english, maths and science. Assign streams according to the following criteria If science > 90 or marks in all are greater than 75 -> Science If marks in all are greater than 60 or equal and less than 75 -> Commerce If marks in all are less than 60 -> Humanities

e=int(input())

m=int(input())

s=int(input())

if s>90 or (e>75 and m>75 and s>75):

print('Science')

elif s>60 and e>60 and m>60:

print('Commerce')

else:

print('Humanites')

Build a meter system for an auto. Take into two inputs. Kilometers Travelled and Stall Time (in minutes). Rate List - First 10 kms - Rs 10 per Km Next 40 kms - Rs 9 per Km Next 100 kms - Rs 8 per Km Any leftover km count - Rs. 6 per Km Rs 5 extra for every minute of Stall Time.

km=int(input('enter km:'))

wt=int(input('enter waiting time:'))

if km<=10:

print((km\*10)+(wt\*5))

elif km>11 and km<=40:

print((100+((km-10)\*9))+(wt\*5))

elif km>41 and km<=100:

print((100+((km-50)\*8))+(wt\*5))

else:

print((100+((km-100)\*6))+(wt\*5))

Enter 3 degit and add that 3 digit:-

number = int(input("Enter a three-digit number: "))

digit\_3 = number%10
digit\_1 = number//100
digit\_2 = (number//10) %10
print(digit\_1)
print(digit\_2)
print(digit\_3)
print(digit\_1+digit\_2+digit\_3)'

## RAnge:-

The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

| **Parameter** | **Description** |
| --- | --- |
| start | Optional. An integer number specifying at which position to start. Default is 0 |
| stop | Required. An integer number specifying at which position to stop (not included). |
| step | Optional. An integer number specifying the incrementation. Default is 1 |

x = range(3, 6)
for n in x:
  print(n)

x = range(3, 20, 2)
for n in x:
  print(n)

## List:-

Lists are used to store multiple items in a single variable.

Lists are one of 4 built-in data types in Python used to store collections of data, the other 3 are [Tuple](https://www.w3schools.com/python/python_tuples.asp), [Set](https://www.w3schools.com/python/python_sets.asp), and [Dictionary](https://www.w3schools.com/python/python_dictionaries.asp), all with different qualities and usage.

thislist = ["apple", "banana", "cherry"]
print(thislist)

print(list(range(3,20)))

print(list(range(3,20,2)))

### While Loop:-

Python while loop is used to run a block code until a certain condition is met.

i = 1
while i < 6:
  print(i)
  i += 1

Take a input from user print alter number

num=1

till\_what=int(input())

while num<=till\_what:

print(num)

num += 2

Take a input from user start & end point print next 3 number

start\_value=int(input())

till\_what=int(input())

while start\_value<=till\_what:

print(start\_value)

start\_value += 3

Print the even numbers:-

start=int(input())

end=int(input())

while start<=end:

if start%2==0:

print(start)

start += 1

Question: You are a bowler and you have to bowl 1 over. (6 balls) "Bowling ball number - ball\_number

ball=1

while ball<=6:

print('bolling number',ball)

ball+=1

print 1 to 10 in single line:-

n=1

while n<=10:

print(n,end=' ')

n+=1

Print 4th multiplication till the user end values:

i=1

mul=4

till=int(input())

while mul\*i<=till:

print(mul\*i,end=' ')

i+=1

Print the multiplication full structure table till 10th value

mul\_table=int(input())

i=1

while i<=10:

print(mul\_table,'\*',i,'=',i\*mul\_table)

i+=1

Get the input from how many time and values from the user and sum the values:

t=int(input('How many times:'))

i=1

while i<=t:

n=int(input('Enter the values to sum:'))

last\_val=0

sum=0

while n!=0:

last\_val=n%10

n=int(n/10)

sum+=last\_val

print(sum)

i+=1

Output:-

How many times:2

Enter the values to sum:123

6

Enter the values to sum:456

15

Count the Given integers

Take T (number of test cases) as input.
For each test case, take integer N as input and Print the count of digits of that number.

t=int(input())

i=1

while i<=t:

n=int(input())

last\_val=0

count=0

if n==0:

count=1

while n!=0:

last\_val=n%10

n=int(n/10)

count+=1

i+=1

print(count)

Reverse the number:-

t=int(input())

while t>0:

t-=1

num=int(input())

rev\_num=int(0)

while (num>0):

rev\_num=(rev\_num\*10) + num%10

num=num // 10

print(rev\_num)

## For Loop:-

A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

Write a program and sum all till N

n=int(input('Enter values:'))

total=0

for i in range(1,n+1):

total+=i

print(total)

Here the default increment value is 1 we can modify the increment values by 2/3/4 ect.

Print 5 to 1 5 is input from user:-

n=int(input('Enter values:'))

for i in range(n,0,-1):

print(i)

When to use while & for loop

| While | For loop |
| --- | --- |
| There is no limit you need to use | There is a limit 1to 100 |
|  |  |

Factorial program:-

n=int(input())

sum=1

for i in range(1,n+1):

sum=(sum\*i)

print(sum)

Jump Statement:-

Pass:-

The pass statement is used as a placeholder for future code.

When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed.

Empty code is not allowed in loops, function definitions, class definitions, or in if statements.

for i in range(5):

if i==3:

pass

print(i,end='')

01234

Continue:-

The continue keyword is used to end the current iteration in a for loop (or a while loop), and continues to the next iteration.

Continue will not execute below content and directly go to the loop starting.

for i in range(5):

if i==3:

Continue

print(i,end='')

0124

Break:-

The break keyword is used to break out a for loop, or a while loop.

for i in range(5):

if i==3:

break

print(i,end='')

012

Get the number from user when user print q out of the loop and count the how many numbers.

count=0

while True:

a=input('Enter the number')

if a=='q':

break

count+=1

print(count)

## ****Question****: Write a loop to print the following numbers - 1,4,7,10,13,16

for i in range(1,17,3):

if i==16:

print(i,end='')

else:

print(i,end=',')

## Nested Loops:-

Writer a program to print the patten

\* \* \*

\* \* \*

\* \* \*

n=int(input('Enter the number'))

for i in range(n):

for j in range(n):

print('\*',end=' ')

print()

Write a program to print the pattern:

1 1 1

2 2 2

3 3 3

n=int(input())

for i in range(1,n+1):

for j in range(1,n+1):

print(i,end=' ')

print()

\*

\* \*

\* \* \*

n=int(input())

for i in range(1,n+1):

for j in range(1,i+1):

print('\*',end=' ')

print()

Write a program to print the pattern:

![](data:image/png;base64...)

n=int(input('Enter the N value:'))

for i in range(1,n+1):

for j in range(1,i+1):

if j%2==0:

print(j,end=' ')

else:

print('\*',end=' ')

print()

Write a program to print the pattern:

![](data:image/png;base64...)

n=int(input('Enter the N value:'))

for i in range(1,n+1):

for j in range((n+1),i,-1):

print('\*',end=' ')

print()

n=int(input())

for i in range(n,0,-1):

for j in range(i,0,-1):

print('\*',end='')

print()

![](data:image/png;base64...)

n=int(input())

for i in range(1,n+1):

for j in range(1,(n\*2)+1):

if j<=i or j>=(n\*2)-i+1:

print('\*',end='')

else:

print(' ',end='')

print()

Write a program to print the pattern:

![](data:image/png;base64...)

n=int(input())

for i in range(n,0,-1):

for j in range(i,0,-1):

if i==1 or i==n or j==1 or j==i:

print('\*',end='')

else:

print('-',end='')

print()

![](data:image/png;base64...)

n = int(input("Enter the N value "))

for i in range(n):

for j in range(n-i-1): #no of spaces - n-i-1

print(" ",end="")

for k in range(i+1):# no of stars

print("\*",end="")

print()

Write a program to print the pattern:

![](data:image/png;base64...)

n=int(input())

for i in range(1,n+1):

for j in range(1,n+1):

if j<i:

print(' ',end='')

else:

print('\*',end='')

print()

![](data:image/png;base64...)

n=int(input())

for i in range(1,n+1):

for j in range(1,n+1):

if j<i:

print(' ',end='')

else:

print('\*',end=' ')

print()

![](data:image/png;base64...)

n=int(input('Enter your integer:'))

for i in range(1,n+1):

for j in range(1,n+1):

if i==1 or i==n or j==1 or j==n:

print('\*',end='')

else:

print(' ',end='')

print()

Google question:-

![](data:image/png;base64...)

n = int(input("Enter the N value "))
for i in range(n): #rows
for j in range(n):#columns
print(max(i,j,n-i-1,n-j-1)+1,end =" ")
print(end = "\n")
#print()

Write a program to print prime number:-

# Take input from user

upto = int(input("Find sum of prime numbers upto : "))

for num in range(2, upto + 1):

for i in range(2, num):

if (int(num % i) == 0):

i = num

break;

#If the number is prime then add it.

if i is not num:

print(num)

10:

2

3

5

Write a program to print multipulation

n=int(input('Enter the multipulation:'))

for i in range(1,n+1):

for j in range(1,10+1):

print(i\*j,end=' ')

print('\n')

Enter the multipulation:5

1 2 3 4 5 6 7 8 9 10

2 4 6 8 10 12 14 16 18 20

3 6 9 12 15 18 21 24 27 30

4 8 12 16 20 24 28 32 36 40

5 10 15 20 25 30 35 40 45 50

Write a Program to find the GCD Greatest common divisior:-

A=int(input())

B=int(input())

x=min(A,B)

for i in range(x,0,-1):

if A%i==0 and B%i==0:

print(i)

break

LCD program:-

A=int(input())

B=int(input())

x=max(A,B)

while True:

if x%A==0 and x%B==0:

print(x)

break

x+=1

****Least Common Multiple (LCM):-****

Write a program to input an integer ****T**** and then for each test case input two integers ****A**** and ****B**** in two different lines and then print T lines containing ****Least Common Multiple (LCM)**** of two given 2 numbers ****A**** and ****B****.

t=int(input())

for j in range(t):

a=int(input())

b=int(input())

g=1

for i in range(1,min(a,b)+1):

if a%i==0 and b%i==0:

g=i

l=(a\*b)//g

print(l)

Find min max in the given range [324,34,346,345,48,679,89,45,45]

n=[324,34,346,345,48,679,89,45,45]

max\_val=0

min\_val=999999999999999

for i in n:

if i>max\_val:

max\_val=i

if i<min\_val:

min\_val=i

print('maximavalue:', max\_val)

print('minumavalue:', min\_val)

Given number is the prime number or not use for and if state ment.

## Functions:-

Def randon\_name()

def tea():

for i in range(0,10):

print('I am making a tea')

sum([3,4])

len('rajeshkannan')

min(4,5,6,8,9,4,3,0)

max(5,3,5,6)

print()

Parameter passing:-

def name\_gretings(name):

print('hello',name)

def General\_info(name,age,gender):

print('My name is: ',name)

print('My age is: ',age)

print('I am a ',gender)

name=input('Enter your name: ')

age=input('Enter your age: ')

gender=input('Enter your Gender: ')

General\_info(name,age,gender)

### Doc Strings:-

### Return values:-

Positional and key word arguments:-

= is keyword it should come last always.

def si(p,t,r=5):

ans=(p\*t\*r)/100

return ans

si(1000,2)

def date\_format(date,month,year,style=0):

if style==0:

print(date,'/',month,'/',year)

elif style==1:

print(month,'/',date,'/',year)

else:

print('invalid syntax')

date\_format(24,'jul',2023)

Scope of the variable: -

Local scope & global scope

a=10

def randon():

a=50

print('inside: ',a)

randon()

print('outside',a)

50

10

10

Lambda function:- (#Anonymous function

#All lambda function are one line.

Data Structure:-

Organize, store

Process

Retrive

List:- (comma Seperated, order(user provided), no limit)

runs\_virat[25,67,100]

Runs\_virat.append(76)

Runs\_virat.insert(1,56)

Get the input from the user and insert into list and insert the values into mentioned position:-

n=int(input())

x=[]

for i in range(n):

a=int(input())

x.append(a)

#print(x)

position=int(input())

value=int(input())

x.insert(position,value)

print(x)

##****Question-1****
Given list of all runs by Virat, print runs made in odd matches (Even Indexes). and store it an another list
runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

def eve(runs):

even\_runs=[]

for i in range(len(runs)):

if i%2==0:

even\_runs.append(runs[i])

return even\_runs

eve(runs)

[62, 74, 12, 122, 81]

Question-3 Given list of all runs by Virat, create a new list of runs made in last 5 matches. runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

def last\_5(runs):

for i in range(len(runs)-5,len(runs)+1):

print(runs[i])

return last\_5

runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

last\_5(runs)

Question-3 Given list of all runs by Virat, create a new list of runs made in first 3 matches. runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

def last\_5(runs):

first\_3=[]

for i in range(3):

first\_3.append(runs[i])

return first\_3

runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

last\_5(runs)

Question 4: given number is perfect square or not:-

class Solution:

# @param A : integer

# @return an integer

def solve(self, A):

c=int(A\*\*0.5)

if c\*c==A:

return 1

else:

return 0

## List slicing:- slice will not give any error in out of range

Slicing will slice the list.

Question-3 Given list of all runs by Virat, create a new list of runs made in first 3 matches. runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

Runs[0:]

Last 5 values in the list : -

runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

print(runs[5:len(runs)])

List the even index values

runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

print(runs[1:len(runs):2])

Odd number : -

runs = [62, 85, 74, 10, 12, 101, 122, 99, 81, 55]

print(runs[0:len(runs):2])

Rotate a list by 1 element. [1, 2, 3, 4, 5] -> last element is removed and added to the start. [5, 1, 2, 3, 4]

lst=[5,6,7,8,9]

print(lst[len(lst)-1:len(lst)]+lst[0:len(lst)-1])

print(lst[-1])

List 2D :

Methods:-

1. pop() # it remove by index will by default remove the last element and use it later

list.pop() removes an element at a particular index.

lst=[5,6,7,8,9]

#print(lst[len(lst)-1:len(lst)]+lst[0:len(lst)-1])

last\_ele=lst.pop()

lst.insert(0,last\_ele)

print(lst)

1. remove() it will remove the values not index value:-

list.remove() removes a particular value from a list.

A.count()

A.reverse()

REVERSED

Question-4 Take a 3X3 matrix as an input fro the user. Given this matrix. Calculate the sum of all the elements in the matrix. Calculate the sum of each row Calculate the sum of each column

## String :-

"random1" +    "random2"

'random1random2'

### ****F-Strings and string formatting****

l =5

b =10

a = l\*b

print("Length = ",l,"Breadth =",b ,"Area is =",a )

Length = 5 Breadth = 10 Area is = 50

#variable  is replaced by curly brackets

print("Length = {} Breadth = {} Area is = {}".format(l,b,a))

Length = 5 Breadth = 10 Area is = 50

Same result we can write this also : -

print(f"Length = {l} Breadth = {b} Area is = {a}")

**Two simple functions** To see the Ascii values :-

ord("a")#\* ```ord()``` function can be used to get the ASCII value of a character.

97

Ascii value into number:-

chr(48)

for i in range(97,123):

print(chr(i),end=" ")

a b c d e f g h i j k l m n o p q r s t u v w x y z

Question-1 Take a string input from user and print that string character by character, with each character in new line. Input: "INDIA" Output: I N D

a = input("Enter you value ")

for i in a:

print(i)

Enter you value INDIA

I

N

D

I

A

n=input('Enter the character:')

print(f'first\_character is:{n[0]}, last\_character is:{n[len(n)-1]}')

Enter the character:INDIA first\_character is:I,

last\_character is:A

Question-3 Take a string input from user. Reverse that string.

n=input('Enter the character:')

print(n[::-1])

Enter the character:india

aidni

Question-4 Take a string input from user. Return "PALINDROME" if the string is a palindrome, otherwise return "NOT A PALINDROME".

n=input('Enter the character:')

original=n

rev=n[::-1]

if original.lower()==rev.lower():

print('Palindrome')

else:

print('Not a palindrome')

print(n[::-1])

Enter the character:srs

Palindrome

Srs

Question-5 Take a string input from user. Print the number of upper case characters in that string.

n=input('Enter the character:')

upp\_count=0

for i in n:

if ord(i)>=65 and ord(i)<=90:

upp\_count+=1

print(f'The count of the upper case is:{upp\_count}')

Enter the character:This is a RANDOM strinG 67890, ^$#@

The count of the upper case is:8

Question-6

You are given a list of numbers between 1 and 256.

Generate a string from the char values of these numbers

Input:

[65, 97, 68]

Output:

AaD

Question-7

Given a string of comma separated values.

Convert it into a string of individual values.

a=input()

Split method:-

a=56,78,99,101

print(a.split(','))

['56', '78', '99', '101']

## String to list:-

for i in a.split(","):

print(chr(int(i)))

8

N

c

e

"AALCLLIA".split("L")

['AA', 'C', '', 'IA']

#### A string can be convertible into list:- list(varible)

a ="Gajodhar"

j = list(reversed(a))

['r', 'a', 'h', 'd', 'o', 'j', 'a', 'G']

#### List to string:- .join(variable)

a ="Gajodhar"

j = list(reversed(a))

"\*".join(j)

‘r\*a\*h\*d\*o\*j\*a\*G'

a='rajesh kannan'

b=list(a)

print(b)

''.join(b)

### Find Method:- .find()

Only first word will find

Replace Function .replace(‘dancing,’singer’)

.Count()

## Tuples:-

### Packing & unpacking:-

## Set:-

## Dictionaries:-

A list can be seen as a kind of dictionary where the key to call the value of each element is the position of this element in the list. For dictionaries, each element is identified by a unique string, called a key, key: value.

#### # empty dictionary

#### >>> my\_dict = {}

>>> my\_dict

#### # dictionary with integer keys

>>> my\_dict = {1: 'apple', 2: 'potato'}

>>> my\_dict

#### # Find the all key & values in dictionary:-

os.keys()

dict\_keys(['1', '2'])

os.values()

dict\_values([‘apple’, ‘potato’])

#### # get element of dict using key

>>> my\_dict[1]

‘Apple’

#### # dict with string keys

>>> my\_dict = {'fruit': 'apple', 'vegetable': 'potato'}

>>> my\_dict['vegetable']

‘potato’

#### # update value

>>> my\_dict = {'fruit': 'apple', 'vegetable': 'potato'}

>>> my\_dict['vegetable'] = 'tomato'

>>> my\_dict

Another Method:-

bbt = {'Sheldon': 1, 'Leonard': 2}
bbt.update({'Penny': 2})
print(bbt)

#### # add item

>>> my\_dict['meat'] = 'beef'

>>> my\_dict

#### # Get length of a list or dictionary:

>>> len(my\_dict)

#### # Merge Dictionaries:-

dict1 = {'ten': 10, 'twenty':20, 'thirty': 30}
dict2 = {'thirty': 30, 'fifty': 50, 'sixty': 60}

dict3 = dict1.copy()
dict3.update(dict2)

Ans:- {'ten': 10, 'twenty': 20, 'thirty': 30, 'fifty': 50, 'sixty': 60}