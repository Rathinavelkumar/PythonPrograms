** Formula for the calculation **

Area of a triangle = square root of (s(s-a)(s-b)(s-c)) 

semi-perimeter=(a+b+c)/2

## Program

    #Python program to find the area of the triangle
    #Formula for the calculation
    #Area of a triangle = square root of (s*(s-a)*(s-b)*(s-c)) 
    #semi-perimeter=(a+b+c)/2

    #Input parameters
    side1 = 15
    side2 = 17
    side3 = 10

    #calculation of semi parameter
    s = (side1 + side2 + side3)/2

    #calculation of area
    area = (s*(s-side1)*(s-side2)*(s-side3)) ** 0.5
    #Round the floating result
    area = round(area, 2)
    print("The area of the triangle is {}".format(area))

## Output

    The area of the triangle is 74.46