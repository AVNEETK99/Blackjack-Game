# Blackjack-Game

Blackjack is a popular card game played in casinos around the world. The objective of the game is to beat the dealer by having a hand that is worth more points than the dealer's hand, without going over 21 points.

In Blackjack, each player is dealt two cards face up, and the dealer is dealt one card face up and one card face down. The player then has the option to "hit" (receive another card) or "stand" (keep their current hand). Players can continue to hit until they choose to stand, or until their hand exceeds 21 points, at which point they "bust" and lose the game.

The value of each card in Blackjack is determined by its number, with face cards (kings, queens, and jacks) each worth 10 points, and the ace being worth either 1 or 11 points depending on the player's choice. The highest possible hand is a "Blackjack," which is achieved by having an ace and a 10-point card in the initial two-card deal.

Overall, the goal of the game is to have a hand that is worth more than the dealer's hand, without exceeding 21 points.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python blackjack.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The first line ```import random``` imports the random module in Python which is used to generate random numbers.

* The ```play_game()``` function defines the main game loop.

* The ```print()``` statements in the beginning of the function display the game's welcome message and instructions.

* The variables ```total_games```, ```dealer_score```, and ```player_score``` are initialized to 0. total_games will keep track of the number of games played, dealer_score will keep track of the dealer's score, and player_score will keep track of the player's score.

* The while loop that follows executes the game for a total of three rounds.

* Inside the ```while loop```, the program prints the current game number and starts dealing cards for the dealer and the player.

* ```dealer_cards``` and ```player_cards``` are initialized as empty lists to hold the cards for the dealer and the player respectively.

* The ```while loop``` that follows appends two cards to the ```dealer_cards``` list and prints the second card dealt to the dealer as "X & _". The first card is hidden from the player.

* The ```while loop``` that follows appends two cards to the ```player_cards``` list and displays the two cards dealt to the player.

* The program checks if the dealer has a Blackjack (i.e., a total card value of 21). If the dealer has a Blackjack, the dealer wins and the program adds 1 to the dealer_score. If the dealer's total card value is greater than 21, the dealer busts and the program adds 1 to the player_score.

* The program prompts the player to either "stay" or "hit". If the player chooses to "hit", a new card is appended to the ```player_cards``` list, and the program displays the new total card value for the player. If the player chooses to "stay", the program displays the total card value for both the dealer and the player, and checks which player has a higher card value. The player with the higher card value wins, and the program adds 1 to their respective score.

* If the player's total card value is greater than 21, the player busts and the program adds 1 to the ```dealer_score```. If the player has a Blackjack (i.e., a total card value of 21), the program adds 1 to the ```player_score```.

* The program displays the current score for the dealer and the player.

* The while loop in step 5 executes three times, after which the game ends.
