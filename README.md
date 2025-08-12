# MIA.training2
##discription
This project is a Python implementation of the Wordle game.  
The game selects a random 5-letter word from a word list, and the player has to guess it within a limited number of tries.  
The interface is built using Tkinter, with a virtual keyboard and colored tiles indicating correct letters and positions.
#Logical structure : 
## intialization :
 Import needed libraries (Tkinter, random).  
   - Load the list of words from `words.txt`.  
   - Choose a random secret word.
#interface :
   - Create the Tkinter window.  
   - Create a grid for the letter tiles.  
   - Create a virtual keyboard using Tkinter buttons.
#the game logic :
- Wait for user input.  
   - After 5 letters are entered, check the guess:  
     - Correct letter & correct position → color green.  
     - Correct letter & wrong position → color yellow.  
     - Letter not in word → color gray.  
   - Update the UI to show the feedback.  
   - If the guess is correct → display a win message.  
   - If the player runs out of tries → reveal the correct word.
#game end :
 - Option to restart or close the game. 
