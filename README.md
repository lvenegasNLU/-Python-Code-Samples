# -Python-Code-Samples


This is example python codes.


# This is code that prints hello world.


Print(“Hello World”)


# This is code greets the user


USER=str(input("enter your name: "))

print("Hello", USER)


#This is a code that greets only me and my instructor with their names.


USER=str(input("enter your name: "))
Luis=print("Hello Luis")
Sunha=print("Good day, sunhwa Nam")
print("Hello", USER)


#This computes the area of a circle


PI = 3.14
radius = float(input(' Please Enter the radius of a circle: '))
area = PI * radius * radius
circumference = 2 * PI * radius

print(" Area Of a Circle = %.2f" %area)
print(" Here is the area, thank you and have a nice day")


#This is a code to compute MPG for a car. 


miles = input('How many miles did you drive on the last tank of gas? ')

gallons = input('How many gallons did you use to fill the gas tank? ')

miles_per_gallon = float (miles) / float (gallons)

print(miles_per_gallon)
print("HERE IS YOUR RESULT, HAVE A NICE DAY")


# Python Program to convert Farenheit to celsius.

 
print("Enter Fahrenheit:")

fahrenheit = float(input())

celsius = (fahrenheit - 32)*5/9

print ("Celsius:", celsius)

# This program calculates the day you will return on. 


STARTDAY = int(input("What day did you leave from 0-6? "))
GONEDAYS = int(input("how many days are you gone? "))
ENDDAY= (STARTDAY + GONEDAYS) % 7
print(ENDDAY)

