# PythonAssignment
A Python program that asks the user to enter their age and then prints "You are a minor" if their age is less than 18, "You are an adult" if their age is greater than or equal to 18 and less than 65, and "You are a senior" if their age is 65 or greater
Age=int(input(Enter your age:))
if Age<18:
    print("you are minor")
elif Age>18 and Age<65:
    print("you are adult")
elif Age>65:
    print("you are senior")
