# EX-NO-6-Pseudo-Random-Number
### Name: Manickam Subbu
### Reg No: 212223060147

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
import random

def generate_numbers(n):

    print("Generating", n, "pseudorandom numbers between 0 and 99:")

    total = 0

    for i in range(n):

        random_number = random.randint(0, 99)

        total += random_number

        print(random_number, end=" ")

    print()

    print("Sum of generated numbers:", total)

    average = total / n
    print("Average value:", average)


print("Pseudo Random Number Generator")

n = int(input("Enter how many pseudorandom numbers you want to generate: "))

generate_numbers(n)

print("Program completed successfully")
```
# OUTPUT:
<img width="1919" height="801" alt="image" src="https://github.com/user-attachments/assets/1de15c80-a505-4fd7-b1da-d382e4701983" />



# RESULT:

     The program is executed successfully
