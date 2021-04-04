# area-of-a-circle
Area of circle with radius given by user

#  Area Of Circle using Radius

pi = 3.141592653589793238
radius = float(input(' Please Enter the radius of a circle: '))
area = pi * radius * radius


print (" Area Of a Circle with the radius " )
print(radius)
print(":")
print ( area )

#A file name from user and it's extension as output

filename = input("Input the Filename: ")
f_extns = filename.split(".")
print ("The extension of the file is : " + repr(f_extns[-1]))
