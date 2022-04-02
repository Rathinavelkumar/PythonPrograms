Program 1 - Generating random numbers in python with the help of random module

## Program 1

    #Random Number Generator
    import random

    #Generate random number between the given range
    result1 = random.randint(1, 100)
    print("Result1 is {}".format(result1))

    #Generate random floating number between 0 and 1
    result2 =  random.random()
    print("Result2 is {}".format(result2))

## Output

    Result1 is 79
    Result2 is 0.49121076629304017

Program 2 - Generation of random numbers without random module

## Program 2

    from time import time

    #user defined random function
    def custom_random(min_value, max_value):
        diff = time() - float(str(time()).split('.')[0])
        random_result = ((max_value-min_value)*diff) + min_value
        return int(random_result)

    result = custom_random(10,100)
    print("The random number is {}".format(result))

## Output

    The random number is 82