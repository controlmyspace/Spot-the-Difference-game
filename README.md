Game
SPOT the Difference!
Objective
The objective of the game is to find the differences between two images as quickly as possible.
Players are shown an original image and the same image with differences. The player that spends less time overall wins the round. 
Levels
There are five levels in the game. Each level consists of an additional difference to spot. Level 1 has four differences. Level 5 has eight.
Game UI


Tech Stack
The game is built with
Python
Pygame library

Approach
To create this game, there needs to be:
Images with differences to represent different levels
Coordinates/positions of the differences to track clicks
A game window
Two timer objects for each player
Split screen to show the original and modified images
A switch for player turns

Changes
I primarily sourced and modified these images through canva.com.
https://www.canva.com/design/DAGd46WsQe4/nSvw-UJxHnK9N8wCh9a78w/edit?utm_content=DAGd46WsQe4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
The game window was initially set at size 800 by 600 but this was changed to 800 by 400 to preserve the quality of the images. 
I added a white border around each image to differentiate from the original (left) to the modified (right).
Once a difference is found and clicked on, a green circle is drawn to mark the spot. I found that this helps to show progression. 

