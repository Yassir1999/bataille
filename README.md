This game is programmed in python, with the use of the Pygame library, the fomowing python libearies are neccessary for the code to run : 
  - random
  - pygame_gui
  - pygame
--------------------------
Definition  and rules :

 Bataille is a card game, where there is two opponents facing each other, the player(you) and the computer, at the start of a game one opponent gets a half deck of cards which extracted randomly from one full deck, and the other gets the other half. each round the player has the draw the first card in his deck(which you can see before drawing) to the board with the ability to shuffle the deck before drawing once, an opponent wins if his drawn card in more valuable than the other opponent's drawn card and gets a point, the first opponent to reach the number of points selected at the start wins the game. How the card's value is determined :

the card with the bigger number has a greater value
if two cards have the same number, the value is determined with the type of the card as follows: diamonds>clubs>heart>spade.
