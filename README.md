# Odd or Even Number Checker


# Step 1: Create a list of 15 numbers 
numbers = [1, 4, 7, 10, 13, 16, 19, 22, 25, 28, 31, 34, 37, 40, 43] 

# Step 2: Loop through each number in the list 
for number in numbers: 
    # Step 3: Check if the number is odd or even 
    if number % 2 == 0: 
        print(str(number) + " is even.") 
    else: 
        print(str(number) + " is odd.")
