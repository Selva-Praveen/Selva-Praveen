def maxnum(x,y,z):
    if (x>y):
        return x
    elif (y>z):
        return y
    elif(z>x):
        return z
x=int(input("enter the number"))
y=int(input("Enter the number"))
z=int(input("Enter the number"))
print(maxnum(x,y,z))
