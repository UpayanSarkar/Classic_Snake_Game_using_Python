# Classic_Snake_Game_using_Python
This is a simple Snake game created using the Python Turtle module.
The player controls a snake on the screen and must eat red fruit to grow longer.
The objective is to eat as much fruit as possible and avoid collisions with the snake's own body and the game borders.
The player's score is displayed at the top of the screen.

How to Play:
Use the arrow keys (Up, Down, Left, Right) to control the snake's direction.
Try to eat the red fruit that appears on the screen to increase your score.
The snake will grow longer as you eat more fruit.
Avoid running into the game borders or colliding with the snake's own body, as this will end the game.
You can exit the game gracefully by pressing the "Escape" key.

Normal Exit:
You can exit the game gracefully by pressing the "Escape" key during gameplay. The game will display a "GAME OVER" message along with your final score.

Abnormal Exit:
If the game encounters an abnormal exit, such as closing the window abruptly or using Ctrl+C (KeyboardInterrupt), it will detect and handle it.
In the case of an abnormal exit, it will display a message indicating "Abnormal exit detected."

Game Cleared:
After the game is finished (either normally or abnormally), it will clear the screen and display a message indicating that the game has been cleared.
It will also set the background color to turquoise.

Error Log:
Any error messages that may occur during abnormal exits are redirected to an "error.log" file. You can check this file for any unexpected errors.
