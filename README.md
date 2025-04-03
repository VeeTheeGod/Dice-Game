# Dice-Game
# A my very first line code, I was able to create a dice game in Pyhthon Language. Enjoy!
import random
while True:
    choice = input('Roll the dice? (y/n):').lower()
    if choice == 'y':
        die1 = random.randint(1,6)
        die2 = random.randint(1,6)
        print(f'({die1},{die2})')
    elif choice == 'n':
        print ('Thanks for playing!')
        break
    else:
        print('Invalid choice!')
