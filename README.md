# Edited by Kasey Egle
# Last edited 2/1/2020
# Problem 1 – Write a program that prints “Hello World” to the screen.

print("Hello World")

# Edited by Kasey Egle
# Last edited 2/1/2020
# Problem 2 – Write a program that asks the user for their name
# and greats them with their name.

name = input("Input your name")
print("Welcome," + name)

# Edited by Kasey Egle
# Last edited 2/1/2020
# Problem 3 – Modify the previous program such that only the users
# Robyn and you are greeted with their names.

name = input("Input your name")

if name == "Robyn" or "Kasey":
    print("Welcome," + name)
else:
    print("Invalid name. Please try again.")

# Edited by Kasey Egle
# Last edited 2/1/2020
# Problem 4 - It is possible to name the days 0 through 6,
# where day 0 is Sunday and day 6 is Saturday.
# If you go on a wonderful holiday leaving on day number 3 (a Wednesday)
# and you return home after 10 nights,
# you would return home on a Saturday (day 6).
# Write a general version of the program which asks for the
# starting day number, and the length of your stay,
# and it will tell you the number of day of the week you will return on.

# Days of week
Sunday = 0
Monday = 1
Tuesday = 2
Wednesday = 3
Thursday = 4
Friday = 5
Saturday = 6

starting_day = int(input('Enter day: [0-6]'))
length_of_stay = int(input('Enter number of nights'))
returning_day = (starting_day + length_of_stay)
print(returning_day)

# Edited by Kasey Egle
# Last edited 2/1/2020
# Problem 5 - Write a program that will compute the area of a circle.
# Prompt the user to enter the radius
# and print a nice message back to the user with the answer.

PI = 3.14159265359
r = int(input('Enter radius'))
Area_Of_Circle = (PI * (r**2))
print(Area_Of_Circle)


# Edited by Kasey Egle
# Last edited 2/1/2020
# Problem 6 - Write a program that will compute MPG for a car.
# Prompt the user to enter the number of miles driven
# and the number of gallons used.
# Print a nice message with the answer.

Miles_Driven = int(input('Enter number of miles driven'))
Gallons_Used = int(input('Enter number of gallons used'))
MPG = (Miles_Driven / Gallons_Used)
print(MPG)

# Edited by Kasey Egle
# Last edited 2/1/2020
# Problem 7 - Write a program that will convert
# degrees Fahrenheit to degrees Celsius.

F = int(input('Enter degrees Fahrenheit'))

# Formula for degrees Celsius

C = 5/9 * (F - 32)
print(C)
