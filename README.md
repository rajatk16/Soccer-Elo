# Soccer-Elo
Python Code for Calculating the Elo Ratings of a Team

### Example
match("Russia", "Saudi_Arabia", 1, 40)

Here, the match function calculates the expected outcome of Match between Russia and Saudi Arabia. Russia's initial Elo rating is 1678, and Saudi Arabia is at 1591. The function will say that the match is won by Russia with Expected score of 0.6.

This value is then taken and used to calculate the new Elo Ratings of both the teams. 

The match function's third argument denotes the actual result of the match. If wdl = 1, then the game was won by Team A, if wdl = 0, then it was won by Team B, and if wdl - 0.5, then the match ended in a draw.

The argument k is the k-factor. You can set it to anything. I have set it to 40 for all the matches except for the Finals, which is set at 60.
