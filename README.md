![Hangman](/assets/images/hangman.gif)

# Hangman

Try to guess the word before you run out of turns!

## Technical Description

The program takes in keyboard events and attempts to pair them with the letters in the current word.  Duplicate letter presses are ignored, and multiple letters in one word show up on one keypress, as expected.

The current word is randomly selected from an array of pre-defined words.  Each keypress loops through the characters of the current word and outputs a new string to be displayed.

The program keeps track of, and displays, letters already guessed.  Buttons to start a new game and reset the current win/loss scores are also included.

Upon successful completion of the game, a picture of the animal being guessed is loaded.

## Technologies Used
* Bootstrap
* jQuery

## Link to Deployed Site
https://hangman.randolphbailey.com
