# Tic-Tac-Toe
A basic tic tac toe game where user plays against computer.

The user will play against a simple artificial intelligence. An artificial intelligence (AI) is a
computer program that can intelligently respond to the player’s moves. 

The board is numbered like the keyboard’s number pad.

#Strategizing with the Game AI
The AI’s strategy for playing Tic-Tac-Toe follows a simple algorithm
—a finite series of instructions to compute a result. A single program can
make use of several different algorithms. 


The AI’s algorithm has the following steps:
1. See if there’s a move the computer can make that will win the game. If
there is, make that move. Otherwise, go to step 2.
2. See if there’s a move the player can make that will cause the computer
to lose the game. If there is, move there to block the player. Otherwise,
go to step 3.
3. Check if any of the corner spaces (spaces 1, 3, 7, or 9) are free. If so,
move there. If no corner space is free, go to step 4.
4. Check if the center is free. If so, move there. If it isn’t, go to step 5.
5. Move on any of the side spaces (spaces 2, 4, 6, or 8). There are no more
steps because the side spaces are all that’s left if the execution reaches
step 5.

