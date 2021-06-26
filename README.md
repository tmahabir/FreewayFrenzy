![Banner](/Images/banner.png)
# Freeway Frenzy
Car driving game coded in C to run on a DE1-Soc board 
* All in one file due to CPUlator constraints
* Final Project for ECE243 - Computer Organization
* To translate into the machine code: https://cpulator.01xz.net/?sys=arm-de1soc
* To play: Load the .c file into CPUlator, key inputs go into "PS/2 keyboard" (Address: FF200100)
* Collaborator: Ji-Oh Kim (https://github.com/jioh-kim)

## How to play
* Press the “Enter” or “Space” button on your keyboard to begin the game.
* Use the “A” key on the keyboard to make your car (silver) go left, or the “D” key to go right. 
* You will see the timer in the top left of the screen and your score in the top right.

## Goal of the game
* Try to last as long as possible by dodging the incoming traffic by moving left or right.

## End of game
* When you crash, the word “BOOM” appears on your screen and you can check your score.
* To play again, press the “Reload” and “Continue” buttons on the CPUlator toolbar.

## Demo
| Start Screen  | Mid-Game | Game Over |
| ------------- | ------------- | ------------- |
| ![Start Screen](/Images/startOfGame.gif)  | ![Mid-Game](/Images/midGame.gif) | ![Game Over](/Images/gameOver.gif) |
