# Stalemate
The worst chess engine possible, Stalemate will find a situation in which a stalemate occurs regardless of how many pieces you are winning by. This project uses Qt Creator and the Stanford C++ Library.

The project is made to solve a self-designed problem. 

Problem statement: Suppose you are playing an opponent in chess. You’re winning by some arbitrary amount: the opponent only has their king but you have a random set of pieces plus your king. Your task is to use your pieces and position in a way to show mercy to your opponent by putting them in stalemate so that the game results in a draw. 

This "chess engine" will take these pieces and recursively backtrack through possible solutions until a stalemate is achieved and the opponent is spared, and then display the result visually.

Some restrictions:
- No pawns
- The opponents king will not occupy edge or corner cases to eliminate hard coded corner cases
- No "moves" will be considered, only the state of the board will be solved for

Example solutions:
