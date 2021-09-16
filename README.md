# python01.py
# creating my first repository CC 01 

  # answer01 
no1 = int(input('Enter First number : '))
no2 = int(input('Enter Second number : '))
no3 = int(input('Enter Third number : '))
def largest(no1, no2, no3):
    if (no1 > no2) and (no1 > no3):
        largest_no = no1
    elif (no2 > no1) and (no2 > no3):
        largest_no = no2
    else:
        largest_no = no3
    print("The largest of the 3 numbers is", largest_no)
 
 
  # answer02
 a = int(input("enter number a:"))
b = int(input("enter number b:"))
c = int(input("enter number c:"))
if a > b and a > c:
    if b > c:
        print("b is the second greatest number")
    else:
        print("c is the second greatest number")
elif b > c and b > a:
    if c > a:
        print("c is the second greatest number")
    else:
        print("a is the second greatest number")
elif c > a and c > b:
    if a > b:
        print("a is the second greatest number")
    else:
        print("b is the second greatest number")

# answer03
a = int(input("enter number a:"))
if a%3 == 0 and a%5 == 0:
    print("Fizz-Buzz")
elif a%3 == 0:
    print("Fizz")
elif a%5 == 0:
    print("Fuzz")         
else:
    print("this number is not divisible by 3 and 5") 
