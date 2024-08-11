import random

options = ("rock", "paper", "scissor")

user_win = 0
computer_win = 0
match_draw = 0

while True:
	
	player = None
	computer = random.choice(options)
	
	while player not in options:
		player = input("Enter your choice (rock, paper, scissor): ").lower()
	
	print(f"player: {player}")
	print(f"computer: {computer}")
	
	if player == computer:
		print("Match draw")
		match_draw += 1
		print()
		
	elif player == "rock" and computer == "scissor":
		print("You won")
		user_win += 1
		print()
	elif player == "paper" and computer == "rock":
		print("You won")
		user_win += 1
		print()
	elif player == "scissor" and computer == "paper":
		print("You won")
		user_win += 1
		print()
		
	else:
		print("You lose")
		computer_win += 1
		print()
		
	if not input("Play again? (y/n): ").lower() == "y":
		print()
		break

print(f"Player wins = {user_win}")	
print(f"Computer wins = {computer_win}")
print(f"Match draw = {match_draw}\n")
print("Thanks for playing")

if user_win > computer_win:
	print('player wins')
elif user_win == computer_win:
	print('match draw')
else:
	print('computer wins')
