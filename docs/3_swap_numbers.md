Program 1 - Swap the numbers with temp variable

## Program 1

    #Swap numbers with temp variable
    num1 = 10
    num2 = 20

    #swap logic
    temp = num1
    num1 = num2
    num2 = temp

    #print the results
    print("num1 : {} | num2 : {}".format(num1, num2))

## Output

    num1 : 20 | num2 : 10

Program 2 - Swap the numbers without temp variable

## Program 2

    #Swap numbers without temp variable - 1
    num1 = 10
    num2 = 20

    #swap logic
    num1 = num1+num2
    num2 = num1-num2
    num1 = num1-num2

    #print the results
    print("num1 : {} | num2 : {}".format(num1, num2))

## Output

    num1 : 20 | num2 : 10

Program 3 - Swap the numbers without temp variable - simplest method

## Program 3

    #Swap numbers without temp variable - 2
    num1 = 10
    num2 = 20

    #swap logic
    num1, num2 = num2, num1

    #print the results
    print("num1 : {} | num2 : {}".format(num1, num2))

## Output

    num1 : 20 | num2 : 10