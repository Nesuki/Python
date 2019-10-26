1. Write a funcion defined as "print_hello" that prints the following message on the screen "Hello teacher!"

```
def print_hello():
	print 'Hello_teacher!'
print_hello()
```

2. Write a function defined as "message_returned" that returns the following message "Hello Teacher!". How is it possible to show this message on the screen? What's the difference from the previous exercise?

```
def message_returned():
	return 'Hello teacher!'
x = message_returned()
print x
 ```

Return is how a function gives back its value, it's often unseen by a human user, but it still can be used by the computer, to show the message you'd have to print the function, other than the use of return, the exercise is the same.


3. Write a function defined as "print_date" which recieves three strings of characters that represent a day, a month, and a year, then print the date in this way "21 of september of 2012"

 ```
def print_date():
	day = raw_input ('Ingrese Dia')
	month = raw_input ('Ingrese Mes')
	year = raw_input ('Ingrese año')
	print day,(' of '),month,(' of '),year
print_date()
 ```

4. Write a function that prints the first hundred integrer numbers.

```
def cien_numeros():
	print range(1,101)
print cien_numeros()
```

5. Write a function defined as "how_many_days" that recieves the month's number as a parameter and returns the amount of days that it has. hint : think about having a list in this way : [["January",31], [“February”, 28], ...]

```

def how_many_days(x):
	mi_lista = [['january',31],['february',28],['march',31],['april',30],['may',31],['june',30],['july',31],['august',31],['september',30],['october',31],['november',30],['december',31]]
	print mi_lista[x]
print ('Insert the month number')
x = input()

print ('the month is'), how_many_days(x)

```

6. Implement a function that shows every multiple of n between n and m * n (n and m should be function parameters)

```
def multiplos_de(n,m):
	n = input('Insert the first number: ')
	m = input('Insert the second number: ')
	x = input('Insert the multiple: ')
	q = range(n, m, x)
	print(q)
print multiplos_de(1,2)
```


7. Write a function that recieves a number as a parameter and shows the multiplication table of said recieved number

```
def tabla_multi(x):
	x = input('Insert the number')
	print x, 2*x, 3*x, 4*x, 5*x, 6*x, 7*x, 8*x, 9*x, 10*x
tabla_multi(1)
```

8. Write a function that calculates the area of a circle, a rectangle, and a triangle. analyse which parameters should these functions recieve.

```
def area_circle():
	diam_circle = float(input("Insert the circles area: "))
	radio = float(diam_circle/2)
	area = float(3.14*(diam_circle)**2)

	print("The circle area is: "+str(area))
area_circle()


def area_rectangle():
	base = (input("Ingrese la base del rectangulo"))
	height = (input("Ingrese la base del rectangulo"))
	area = base*height
	print ("The rectangle area is : "+str(area))
area_rectangle()

def area_triangle():
	b = input('Insert triangle base: ')
	h = input ('Insert  triangle height: ')
	print b*h/2
area_triangle()

```