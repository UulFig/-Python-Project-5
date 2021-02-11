# -Python-Project-5
#5 Count to a a number(input) using while Loop

def inputNumber(message):
    while True:
        try:
            userInput = int(input(message))
        except ValueError:
            print("Please, put an valid number.\n")
            continue
        else:
            return userInput
            break
i = 0
number = inputNumber("Choice a number to count. :)\n")

while i < int(number):
    print(i + 1)
    i = i + 1
else:
	print(f"Work is done! I\'ve counted {number} times.\n")
