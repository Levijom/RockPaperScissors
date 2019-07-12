# RockPaperScissors
A puzzle of rock paper scissors

Rock Paper Scissors is a simple circular game, where paper beats rock beats scissors beats paper.  I want to know how it works in a large group environment.  The game goes as follows;
n-number of teams
k-number of players on each individual team (k may be different for each team)
The players are allowed to strategize, but the other team will be able to hear.
  I may decide that the team with the most players left in a round will "strategize" first, then the next smaller, then the next, all the way till 0
  "Strategizing" is simply letting everyone know what each player on a team plans to do in order to have optimal winning.
It is assumed that all players will make the best statistical choice to win.

For example;
Team 1 = 2 players (T1P1 & T1P2)
Team 2 = 1 player (T2P1)

ROUND 1:
Team 1 has the advantage, so they strategize first.
Team one annouces "T1P1 goes ROCK, T1P2 goes PAPER"
  This is such that they cannot possibly lose, and could potentially win, IFF T2P1 chooses SCISSORS
Team 2 recognizes their best option is PAPER
T2P1 PAPER beats T1P1 ROCK
END OF ROUND 1:
  T1P2 & T2P1

ROUND 2:
No team has the advantage, so randomly Team 2 "Strategizes" first.
Team 2 needs no strategy (as there is only 1 player) and will choose randomly between ROCK, PAPER, or SCISSORS
Team 1 recieves no input from Team 1, and only has 1 player, so will also choose randomly between ROCK, PAPER, or SCISSORS
END OF ROUND 1:
50% chance of either team winning

End of match.



