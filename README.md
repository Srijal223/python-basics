# python-basics
It consists some basic codes of python with comments for better understanding and practise for begginers.

#question 1 welcome message
a= input("enter message:")
print (a)

#question 2 sum of three numbers
a=int(input("enter a number:"))
b=int(input("enter a number:"))
c=int(input("enter a number:"))


#question 3 area of rectangle
l=float(input("enter length:"))
b=float(input("enter breadth:"))
area=l*b
print(area)

#question 4 to calculate bmi
weight=float(input("enter weight"))
height=float(input("enter height"))
BMI=(weight/(height*height))
print("BMI is :",BMI)

#question 5 cube of given number
n=int(input("enter a number:"))
cube=n**3
print("cube is :",cube)

#question 6   km to miles
Dist=int(input("enter distanc in km:"))
miles=Dist*0.621371
print("miles :",miles)

#question 7 tonne to quintal and kg
tonne=float(input("enter tonne:"))
quintal=tonne*10
kilogram=tonne*1000
print("Quintal is:",quintal)
print("Kilogram is:",kilogram)

#question 8 swap btw two numbers
a=int(input("enter a number:"))
b=int(input("enter a number:"))
a,b=b,a
print(a)
print(b)

# calculator 
a=int(input("enter first  number:"))
b=int(input("enter second number:"))

sum=a+b
print("addition is:",sum)
sub=a-b
print("subtraction is:",sub)
mult=a*b
print("multiplication is:",mult)
div=a/b
print("division is:",div)
mod=a%b
print("modulus is:",mod)

