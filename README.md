# Rock-Paper-Scissors

import random
#Variables
computer = random.randint(1,3)
print ("Let's play Rock, Paper, Scissors!\n")
#Start
player = input("Type Rock, Paper, or Scissors here:")
print ("You chose " + player + ".")

if (computer == 1):
    print ("Computer chose Rock.\n")
elif (computer == 2):
    print ("Computer chose Paper.\n")
elif (computer == 3):
    print ("Computer chose Scissors.\n")
if ((player.lower() == 'rock')and computer == 1):
    print ("Rock Vs. Rock.\n Tied game!")
elif ((player.lower() == 'rock')and computer == 2):
    print ("Rock Vs. Paper.\n Paper wraps rock.\n Computer Wins!.")
elif ((player.lower() == 'rock')and computer == 3):
    print ("Rock Vs. Scissors.\n Rock crushes scissors.\n You win!")
elif ((player.lower() == 'paper')and computer == 1):
    print ("Paper Vs. Rock.\n Paper wraps rock.\n You win!")
elif ((player.lower() == 'paper')and computer == 2):
    print ("Paper Vs. Paper.\n Tied game!")
elif ((player.lower() == 'paper')and computer == 3):
        print ("Paper Vs. Scissors.\n Scissors cuts paper\n. Computer Wins!")
elif ((player.lower() == 'scissors')and computer == 1):
    print ("Rock vs. Scissors.\n Rock crushes scissors.\n Computer Wins!")
elif ((player.lower() == 'scissors')and computer == 2):
    print ("Scissors Vs. Paper.\n Scissors cuts paper.\n You win!")
elif ((player.lower() == 'scissors')and computer == 3):
    print ("Scissors Vs. Scissors.\n Tied game!")
