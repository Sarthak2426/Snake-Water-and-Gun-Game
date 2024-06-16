# Snake-Water-and-Gun-Game

Welcome to the Snake Water Gun Game! This is a simple and fun game you can play against the computer. The game is similar to "Rock Paper Scissors" but with a twist. You get to choose between Snake, Water, and Gun. The rules are as follows:

Snake drinks Water, so Snake wins against Water.
Water douses Gun, so Water wins against Gun.
Gun shoots Snake, so Gun wins against Snake.
If both you and the computer choose the same item, it's a tie.

How to Play
Step-by-Step Instructions
Run the Code: Execute the script in a Python environment.
Choose Your Move: When prompted, input your choice:
s for Snake
w for Water
g for Gun
Game Mechanics:
The computer will randomly choose one of the three options.
The winner for each round will be displayed along with the scores.
The game will continue for a predefined number of chances (default is 5).
Game Over: After all chances are used, the game will display the final scores and declare the winner.
Example Gameplay
plaintext
Copy code
			Snake Water Gun Game

Choose s for the snake
Choose g for the gun:
Choose w for the water

Snake, Water and Gun: s
You chose s and computer chose w
You win this round:
Computer score: 0
Your score: 1
4 chances left from 5

Snake, Water and Gun: w
You chose w and computer chose g
You win:)
Computer score: 0
Your score: 2
3 chances left from 5

...

Game Over
Congratulations:) Well Played
You Won
Your score: 3
Computer score: 2
Installation
No special installation is required. Just make sure you have Python installed. The game uses basic Python libraries such as random for generating computer choices.

Libraries Used
numpy (not utilized in the current version but imported)
pandas (not utilized in the current version but imported)
random (used for generating random choices for the computer)
