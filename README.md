# Othello
Final Project for Richard Kelley's AI Class

author Harrison Stanton


This program emulates the game othello. The user has the option of chosing what plays each player.
The options are AI, random, and player controlled. The game board can be disabled for sake of running statistics on the games.
The algorithm I used for the AI is a version of minimax, where all the possible moves are first found.
For each move the score is calculated for all possible responses. The value of the best score of the response is assigned to each move.
Then the move that generates the minimum best response from the other player is chosen.
This algorithm could be easily improved by adding addition depth to the search, by optimizing for the corners, and by optimizing for limiting the other players moves. 

Over a test sample size of 300 games, the algorithm beat the random player 231 times, the random player won 63 times, with 6 draws.
With a 77% win rate it is sufficent to say this algorithm performs better than random.

Looking over the games it seems that the AI is good at punishing poor moves, however it is rather terrible against long term strategy and stable plays.

