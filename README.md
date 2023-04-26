# simon-game

Simon Game

This is a simple web-based game called Simon, where the player needs to follow the pattern of randomly generated colors. The game starts with a single color and each level increases the sequence length by one. The game ends when the player fails to follow the pattern.

How to Play:

-Press any key to start the game.
-Watch and remember the sequence of colors played by the game.
-Click on the colors in the same order as they were played by the game.
-If you get the sequence correct, the game will play the next color in the sequence.
-If you get the sequence wrong, the game will end and you will need to start over by pressing any key.

Code Structure:

buttonColours: An array of four colors used in the game.
gamePattern: An array that stores the randomly generated sequence of colors.
userClickedPattern: An array that stores the user's input.
started: A boolean value to check if the game has started or not.
level: An integer that represents the current level of the game.
$(document).keypress: A jQuery event listener that waits for the user to press any key to start the game.
$(".btn").click: A jQuery event listener that waits for the user to click on the colored buttons.
checkAnswer: A function that checks if the user's input matches the game pattern.
nextSequence: A function that generates the next color in the game sequence.
animatePress: A function that adds a visual effect to the colored buttons when they are clicked.
playSound: A function that plays a sound when a button is clicked or a game event occurs.
startOver: A function that resets the game when the player loses.

Technologies Used:

HTML
CSS
JavaScript
jQuery

Credits:

This game was inspired by the classic Simon game from the 1980s. The code for this game was written by [insert your name here].