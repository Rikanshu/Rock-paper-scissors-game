  # Rock-paper-scissors-game

# Python Rock paper Scissor Game

import random 

choice = ["rock","paper","scissors"]
while True:
 computer: str = random.choice(choice)

 user = input("choose rock or paper and scissors: ").lower()
 print("computer choose",computer)
 
 if user == computer: 
    print("tie")

 elif user == "rock" and computer == "scissors":
    print("you win") 
    
 elif user =="paper" and computer == "rock":
    print("you win")
 elif user == "scissors" and computer == "paper":
    print("you win")
 elif user in choice:
    print("you lose")
 else:
    print("invalid input")         


 replay = input("do want to replay this game (yes / no )").strip().lower()
 if replay =="no":
    print("thank you for playing this game")
    break





      
