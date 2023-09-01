# Python-basic-programs-
#Program for area of rectangle
def rectangle_area(length,width):
    areaofrectangle=length*width
    return areaofrectangle
    
length=int(input("Enter the length og rectangle:-"))
width=int(input("Enter the width of the rectangle:-"))
areaofrectangle=rectangle_area(length,width)
print("The area of the rectangle is",areaofrectangle)
