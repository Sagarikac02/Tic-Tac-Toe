# Tic-Tac-Toe
Go through each possible move, and for each such possible move, turn the board around, pretend to be the other player (that's the player*-1 part), and try each possible move. thisScore is set to the negative return value from the recursive call to minimax, since good for the other player equals bad for ourselves.
