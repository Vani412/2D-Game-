# 2D-Game-
a=27
print(" This is a guessing game. There will be 2 parts and each part will have 3 levels.")
print("You will get clues and only 1 chance for each level if you guess the correct number then you will be promoted to the next level.")
Player=input("Enter your name: ")
print("You have to guess a two digit number.")
print("The first digit ranges from 1-3, the second digit ranges from 5-8")
x=int(input("Guess the number: "))
if x==a:
    print("Bravo!! You have leveled up!!")
else:
    print("The number is 27!!")
print("Now you have to guess a three digit number.")
print("The first digit is a prime number, the second digit is a factor of 240 and the third digit is a number ranging from 2-6 ")
b=345
x=int(input("Guess the number: "))
if x==b:
    print("Amazing!! You have reached the final level of part 1!!")
else:
    print('The number is 345!!')
print("Now you have to guess a four digit number.")
print(" The second digit is a prime number.  The fourth digit is a magic number")
c=4104
x=int(input("Guess the number: "))
if x==c:
    print("Congratulations!! You have reached Part 2. Do you know 4104 is a Hardy-Ramanujan number!!!")
else: 
    print("The number is 4104!! Do you know 4104 is a Hardy-Ramanujan number!!!")
