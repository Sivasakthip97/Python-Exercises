#Guess the number game
import random
import math 
guess=1


def userguess():
    print('Guess',guess,':')
    while True:
        num=input()
        try:
            num1=int(num)
            return num1
            break
        except ValueError:
            print('Invalid number\nTry again')

def random_numgen():
    random_num =random.randint(1,100)
    return random_num



#main fn starts
print('Game Starts:\nYou Got 3 Guesses!!\n,Guess the number between1 to 100',)
random_num=random_numgen()


while(guess<=3):
    userguess_num=userguess()
    check = userguess_num - random_num
    if(userguess_num==random_num):
       print('Awesome You Won!')
       guess=4
    elif(check<=10):
         print('your guess is near to random number')
         guess+=1
         if(guess>3):
             print('OOPS Sorry ! Game over...')
    else:
         print('your guess is so far to random number')
         guess+=1
         if(guess>3):
              print('OOPS Sorry ! Game over...')

#print('userguess:',userguess_num)
