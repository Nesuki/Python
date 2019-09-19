### Part I : Identify if the next codes produce an error, justify. ###
---
1:
``` 
x=1
print X
``` 

The variable “X” is not defined, because the defined variable is a lowercase “x”


2:

``` 
num.next =4
``` 
Dot produces an error, it is needed to use _ if its wanted to use spacing for a variable


3:

``` 
y=1
print y+x 
``` 

“x” is not defined unlike “y”

---

### Part II: Explain what these codes do. ###


1:

``` 
x=input ('insert a number')
print x+1
``` 

asks for the user to insert a number , then shows the result of the sum of an unit to the number that has been inserted previously
2:

``` 
num=input('insert a number')
print num+'1'
``` 

The intended use of this code was to add an unit to the inserted number, however this code gives an error when executing it.
3:

``` 
y=4
Y='hello'
print y
``` 

Displays “4” however, it doesnt  do anything with the “Y” variable

---

### Part III: Type the code according to the instructions below ###

1: Ask for a number input and print the triple 

``` 
x=input ('insert a number')
print x*3
2: Ask for a name and print a greeting
nom=raw_input ('Insert your name')
print ('Hello'),nom
``` 

3: Ask for a number and then divide it by half

``` 
x=input ('Insert a number')
print x/2
``` 

4: Ask for 4 notes and print the average

``` 
x=input ('type the note 1: ')
y=input ('type the note 2: ')
z=input ('type the note 3: ')
print x+y+z/3
``` 

---
### Part IV: More exercises with numbers. ###

5: Ask for the base and height of a triangle and show its area 

``` 
b=input('Insert triangle base: ')
h=input ('Insert  triangle height: ')
print b*h/2
``` 

 6: Ask for the circle’s diameter and calculate their area and perimeter (P = π * D y A = π * r).
 
``` 
diam_circulo=float(input("Inser the circle diameter: "))
radio=float(diam_circulo/2)
area=float(3.14*(diam_circulo)**2)
perimetro=float(2*3.14*(diam_circulo))
print("The area circle is: "+str(area))
print("The circle perimeter is: "+str(perimeter))
``` 

7: ask for 2 numbers and show the division between them and the remainder

``` 
primernum = input ("Insert the first number: ")
segundonum = input ("Insert the second number: ")
print "the division between the first and the second number is : ", primernum/segundonum
print "the remainder of the number is: ", primernum % segundonum
``` 

8: if you have the variables n1=124.25 y n2= “33.40”. do the necessary convertions to know the integrer division between them and the remainder

``` 
n1=124.25
n2=33.40
n2=float(n2)
div=n1//n2
div2=n1/n2
rem=n1%n2
print div,div2,res
``` 



9: Ask for the height, width and lenght of a pool, calculate the volume and the amount of liters that it has (take in mind that 1000cm3=1 liter)

``` 
height=float(input('insert the height of the pool in cm: '))
width=float(input('insert the width of the pool in cm: '))
lenght=float(input('insert the lenght of the pool in cm: '))
volume=height*width*lenght
liters=volume/1000
print 'the pool volume is ', volume, 'cm3'
print 'the pool capacity is ', liters, 'liters'
``` 

10: Ask for the width and lenght of a terrain and show how many grass panels are needed to purchase (panels are 60x60 cm)

``` 
terrain_width=input("insert the terrain width: ")
terrain_lenght=input("insert the terrain lenght: ")

grass_panel= 0.60*0.60
terrain_area= int(terrain_lenght*terrain_width/grass_panel)
print "the amount of grass panels thats needed to purchase are",terrain_area, "panels"
``` 
11: ask for 4 bought products data, with their amount and unit price and show the spending of each product and the total

``` 
q_product1 = input ("insert the first product quantity: ")
p_product1 = input ("insert the first product price: ")
q_product2 = input ("insert the second product quantity: ")
p_product2 = input ("insert the second product price: ")
q_product3 = input ("insert the third product quantity: ")
p_product3 = input ("insert the third product price: ")
q_product4 = input ("insert the fourth product quantity: ")
p_product4 = input ("insert the fourth product price: ")
print "total cost of the first product:","$",q_product1*p_product1
print "total cost of the second product:","$",q_product2*p_product2
print "total cost of the third product:","$",q_product3*p_product3
print "total cost of the fourth product:","$",q_product4*p_product4
print "total cost of all the products:","$",(q_product1*p_product1)+ (q_product2*p_product2)+(q_product3*p_product3)+(q_product4*p_product4)
``` 

12: ask for a price and split in bills of 2, 5, 10 , 20, 50 , 100 and 500.

``` 
price=int(input("insert the amount to split: "))

bill500=(price//500)
r500=(precio%500)
print ("500 bills: ",bill500)

bill100=(r500//100)
r100=(r500%100)
print ("100 bills: ",bill100)

bill50=(r100//50)
r50=(r100%50)
print("50 bills: ",bill50)

bill20=(r50//20)
r20=(r50%20)
print("20 bills: ",bill20)

bill10=(r20//10)
r10=(r20%10)
print ("10 bills: ",bill10)

bill5=(r10//5)
r5=(r10%5)
print("5 bills: ",bill5)

bill2=(r5//2)
r2=(r5%2)
print ("2 bills: ",bill2)
``` 
--- 
### Part V: More text exercises. ###

13: Ask for 3 words and show a text with initials from each one

``` 
print 'Insert 3 words'
Input1=raw_input()
Input2=raw_input()
Input3=raw_input()
print Input1[:1]+Input2[:1]+Input3[:1]
``` 

14: Ask for 5 words and show the amount of letters they have in total

``` 
print ('Insert 5 words')
Input1 = raw_input()
Input2 = raw_input()
Input3 = raw_input()
Input4 = raw_input()
Input5 = raw_input()
print ('the total amount of letters these words have are')
print len(Input1)+len(Input2)+len(Input3)+len(Input4)+len(Input5)
``` 

15:ask for a verb in infinitive and show their termination  (ar, er o ir) (these are Spanish verb terminations)

``` 
Input=raw_input ('insert a Spanish verb in infinitive: ')
print 'the verb termination is : '
Len = len(Input);
Output=Input[Len-2:]
print Output
``` 

16: Ask for name, surname, student number and class number and class number for a student that wishes to enroll, show the next message “the enrollement to the class <number> requested by the student <surname>, <name> is being processed

``` 
print 'insert ur name'
name=raw_input()
print 'Insert your surname'
surname=raw_input()
print 'insert student number'
StudentN=raw_input()
print 'insert desired class number'
Com=raw_input()
print 'the enrollement to the class '+Com+' requested by the student ' + Apellido,Nombre+ ' is being processed'
``` 

17: Ask for 4 units of data : who, what has been done, when and how. Then show the next news headline:
“Newsflash!, the person xx, in the day xx, has done xx, in this particular way xx”

``` 
who=raw_input ('who ')
what=raw_input ('what has he done ')
when=raw_input('when has he done it ')
how=raw_input ('how has he done it ')
print ('Newsflash!, the person '),who,('in the day '),when,('has done '),what,('in this particular way: '),how
``` 

18: Ask for someone’s name, surname and day, month and year they have been born, make a password with this data (their password would be their initials next to an underline and their year of birth) then display it
 
 ``` 
nom=raw_input ('Insert your name: ')
ap=raw_input ('Insert your surname: ')
dia=raw_input('Insert your day of birth: ')
mes=raw_input('insert the month of birth: ')
anio=raw_input('insert  the year of birth: ')
print ('your password is: '),nom[:1],ap[:1],('_'),anio
``` 

19:Ask for an user’s mail account and show their user and domain (use find)

``` 
email = raw_input("Please insert your email: ")
at = email.find("@")
print "The username is: ", email[0:at]
print "the domain is: ", email[at+1:]
``` 
