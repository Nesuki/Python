

### Part I : Concepts ### 

1.	Whats the difference between input() and raw_input()? if you'd need to insert a number from the keyboard, which one you'd use?

input is used for numbers and raw_input for characters, the one you'd need to use for numbers is input


2.	Define the difference between a list and a tuple

A List is modificable, you can add or substract elements from it, the tuple is not modificable, therefore you can't do the things mentioned in a tuple compared to the list.

---


### PART III Datos, Variables and Datatypes: ###

1:  Write a program that prints on the screen your name and age, in the screen it should appear "my name is xxxx and my age is xx"

```
Nom=raw_input ('Insert your name')
Edad=raw_input ('Insert your age')
print ('My name is '+Nom+ ' and I am ')+Edad+(' years old')
```

Have you used variables? which ones?

```
Nom , Edad
```

have you used values? which ones?

```
'Inserte su nombre' , 'Inserte su edad'
```

What commands have you used?

```
raw_input , print
```

2: Write a program that recieves a name inserted by the user and print a greeting alongside it. 
It should appear as “¡Hello xxx!”

```
Nom=raw_input ('Insert your name')
print ('Hello '+Nom+'!')
```


Have you used variables? which?

 ```
Nom
```
Have you used values? which ones?

```
Nom=raw_input, 'inserte nombre'
```
have you used operators? which ones?

```
+
```

What commands have you used?

```
print, raw_imput
```

3: Write a program that recieves a name and age being inserted by the user n print the information given by the user.

On the screen it should appear "your name is xxx and your age is xx"

```
Nom=raw_input ('insert your name')
Edad=raw_input ('insert your age')
print ('Your name is '+Nom+' and your age is '+Edad)
```


Have you used variables? which ones?

```
Nom, Edad
```

have you used values? which ones?

```
'Inserte nombre', 'Inserte edad'
```

have you used operators? which ones?

```
+
```

What commands have you used?

```
raw_input, print
```

4: Run the next codes and identify in which case in what value does the variable x ends, justify your answer.

a) 
```
x= 10 X= x**2
print x
```

"10" prints the lowercase x variable with 10 value


b)
``` x=30
 x= x % 4
print x 
```

30 prints the lowercase x variable with 30 value

c) 

```
a= “4” b= “3” x= a + b print x
```

“43” a+b is ab, therefore “4”+”3” is “43”

d) 
```
a= “4” b= 3
x= a * b print x
```

“444” multiplies 3 times the character “4”	

e) 
```
a= 4 
b= 3 
x= “a” * b print x
```

“aaa” multiplies “a” 3 times, which is the b variable

5:

Run the next code and say what does it do and what programming element are being used: variables, values, operators and commands

a- 

```
print 'hello'
```

prints hello

command : print

value "hello"

b- 

```
print 2
```

prints 2 on the screen

command:print

value "2"

c- 

```
nombre=raw_input('Insert a name') 
print nombre
```

Asks the user to write a name, then displays it on screen

Command: raw_input, print

Value: 'Insert a name'

Variable : nombre


d-

```
edad=input('Insert your age')
 print edad
```

Asks the user to type their age, then displays it on screen

command: print , input

value: 'Insert your age'

Variable: edad

e-

```
print 2*3
```

prints the multiplication of 2 and 3

values: 2 , 3

command : print

operator: *


f-

```
print 4%2
```

prints the remainder between 4 and 2

values: 4 , 2

command : print

operator: %

g- 

```
num1=raw_input('Insert a number') num2=raw_input('Insert another number') 
print num1+num2
```

Asks the user to insert 2 numbers then displays them on screen, these has to be written in characters and not in numbers.

Values: 'Insert a number' , 'Insert another number'

commands: raw_input , print

operators: +

Variables : num1 , num2


h- 

```
num1=input('Insert a number')
num2=input('Insert another number') print num1+num2
```

Asks the user to insert a number, then another, then displays it on screen

Values: 'Insert a number' , 'Insert another number'

commands : input , print

operators : +

Variables : num1 , num2


6:  

Assign the variables num1 and num2 the different values indicated in the table

Do the next calculations with the indicated operators

Write the results in this table and justify

| num1 value|  num2 value  | operation| value result |   justification|
| -----------   | -----------    | ----------| -----------   |------------|
| 5             | 2              | //        | 2              |integrer division|
| 7.2 | 9.8  | * | 70.56 |multiply|
| 7 | 3.1  | -| 3.9 |substract|
| 10.45| 7  | +| 17.45|add|
| “argentina”|3  | *| argentinaargentinaargentina|multiply|

---

### PART III: ###
### Run the next codes: ### 

a)	

```
tupla=(1,True,['a','b','c'], "hola")    tupla[1]=False
```

¿Cuál es el resultado de esta ejecución?. Justificar

Se quiere modificar el valor True por False, pero como es una tupla, es inmutable, por lo tanto da error de asignacion. 

b)	

```
tupla=(1,True,['a','b','c'], "hola")     tupla[2][0]='b'  
```

Whats the result of this run? justify.

It seeks to modify the true value to false, but gives asignation error because its a tuple, and tuples are immutable

According to this list: lista=[1,True,['a','b','c'], "hola"]. run the different commands and describe the results
a) 

```
print lista[2]

```

prints ['a','b','c']

b)	

```
print lista [4]	
```

tries to print a list's element but it's out of range, theres not enough elements in the list

c)

```
lista.append (False)     print lista
```

adds (False) to the list n then prints the list

d) 

```
lista=[1,True,['a','b','c'], "hola"]      
del lista[2]
print lista
```  
deletes the element in position 2 ['a','b','c'] and prints the list without the second element, the rest are unchanged.

---
### PART IV: ###

1: show 5 times the string “Hello”

```
str="Hello"
print str * 5
```


2: Show the ASCII code of the next characters “A”, “a” y “0”

```
print ord ("A"),ord("a"),ord("0")
```


3: Design a program that starting from the value of the side of a square (3 meters) shows the value of its perimeter (in meters) and their area (in square meters)

(The perimeter should give you 12 meters and the area 9 square meters.) 

```
l=3
p=l*4
a=l*l

print ('The square perimeter is')  ,p,  ('meters')
print ('The square area is') ,a, ('square meters')
```



4: Write a program that reads a number written by the user and show if its positive, negative, or zero.	


```
x=input ('Insert a number')
if x>0
	print ('Its positive')
else:
print ('Its not positive')
```

5: Write a program that identifies if a number is divisible by 6

```
x=input ('Insert a number')
if x%6==0:
	print ('is divisible by 6')
else:
	print ('not divisible by 6')
```

6: Write a program that reads two numbers "n" and "m" and determine if m is divisible by n

```
n=input('insert the first number: ')
m=input('insert the second number: ')
divisible= n>0
print "The number ",m, " is divisible by the number ",n,"=",divisible
```

7: Design a program which given a number from 1 to 7 it determines what day of the week it represents : 1- sunday to 7 - saturday. What would happen if a number is bigger than 7?

```
x=input('insert a number')
if x==1:
	print('Sunday')
if x==2:
	print('Monday')
if x==3:
	print('Tuesday')
if x==4:
	print('Wednesday')
if x==5:
	print('Thrusday')
if x==6:
	print('Friday')
if x==7:
	print('Saturday')
if x>7:
	print('This number doesnt represent any day of the week')
if x<1:
	print('This number doesnt represent any day of the week')
```

If a number bigger than 7 is inserted nothing would appear, therefore i added two conditionals in case someone inserts a number bigger than 7 or smaller than 1

8: Write a program that prints the first hundred integrer numbers.

```
x = range(0, 101)
print(x)
```

9: Modify the previous exercise, in a way that it only prints pair numbers

```
x = range(0, 101,2)
print(x)
```

10: Write a program that prints the multiples of 7 that are within the number 123 and 546

```
x = range(123, 546,7)
print(x)
```

11: Implement a program that shows every multiple of n between n and m · n, both inclusively, where n and m are numbers inserted by the user

```
n=input('insert the first number: ')
m=input('insert the second number: ')
x=input('insert the multiple: ')
q=range(n, m, x)
print(q)
```

12: Write a program that shows the multiply table of a number inserted by the user

```
print x, 2*x, 3*x, 4*x, 5*x, 6*x, 7*x, 8*x, 9*x, 10*x
```


