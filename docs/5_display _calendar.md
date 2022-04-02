Display the calendar based on the user input year and month 

## Program

    import calendar

    #User inputs
    input_year = int(input("Enter the year : "))
    input_month = int(input("Enter the month : "))

    #Display the calendar
    print(calendar.month(input_year, input_month))

## Output

    Enter the year : 2018
    Enter the month : 3
    March 2018
    Mo Tu We Th Fr Sa Su
            1  2  3  4
    5  6  7  8  9 10 11
    12 13 14 15 16 17 18
    19 20 21 22 23 24 25
    26 27 28 29 30 31