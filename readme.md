&nbsp;

# TIC TAC TOE

My first project at general assembly is the game of tic tac toe. It was created using javascript, css and html.

&nbsp;

## Link to live version
--------------------------------

#### https://george-moon.github.io/TIC-TAC-TOE/

--------------------------------

## Instructions on how to play

To play the game of tic tac toe

```
To play against another person press the start button

To play against the computer press the computer button and then start
```

The game will start

```
The player must choose a square to mark with a "O"

Dependant on whether you choose to play a person or the computer:
    
    - Player two must choose a square not already taken to mark with an "X"

    - The computer will automatically choose a square to mark with an "X"

The turns alternate until there is a winner or a draw.
```
## How to win!
```
The aim of the game is to get three "O" or "X" in either a vertical column, horizontal row or diagonal line.

If neither player achieves this and there are no spaces remaining the game is declared a draw!
```

## About the game.

The game was constructed using html, css and javascript. The logic of the gameplay is as follows:

- Event listeners assigned to start / reset / computer button
- When start button is pressed event listeners are generated for the rest of the game board
- The game will then wait for a square to be chosen by player one
- The game will check the status of the current turn
- It will then assign the current position chosen to the correct player
- Once a move has been made the game will check to see if there is a win / draw condition on the gameboard
- If neither are found gameplay will continue
- Computer / player two will decide the next move and the status of the current turn will change and the move will be assigned
- This flow of each player taking a turn will be repeated until a win / draw condition is met. 
- A message will be output to declare the winner / draw and the gameboard event listeners will be removed
- To reset the game the reset button must be hit and all selected tiles will refresh and the game will start again.


## Built With

* [Javascript](https://www.javascript.com)
* CSS
* HTML

## Authors

* **Morgan Willock** - [Git hub - George Moon](https://github.com/george-moon)

## Acknowledgments

* DT for helping fix my animation issues
* Hat tip to anyone who helped along the way

