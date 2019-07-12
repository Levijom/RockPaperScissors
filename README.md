# RockPaperScissors
A puzzle of rock paper scissors

Rock Paper Scissors is a simple circular game, where paper beats rock beats scissors beats paper.  I want to know how it works in a large group environment.  The game goes as follows;
n-number of teams
k-number of players on each individual team (k may be different for each team)
The players are allowed to strategize, HOWEVER the other team will be able to hear.  The team with the most players left in a round will "strategize" first, then the next smaller, then the next, all the way till the smallest.  "Strategizing" is simply letting everyone know what each player on a team plans to do in order to have optimal winning.  It is assumed that all players will make the best statistical choice to win.

For example;
Team 1 = 2 players; (T1P1) & (T1P2)
Team 2 = 1 player;  (T2P1)

ROUND 1:
Team 1 has the advantage, so they strategize first.
The optimal strategy is to have each player choose a different option.  This way they cannot possibly lose, and could potentially win, IFF T2P1 chooses SCISSORS.
Team one annouces "T1P1 goes ROCK, T1P2 goes PAPER"
Team 2 recognizes their best option is PAPER
T2P1 goes PAPER
T2P1 PAPER beats T1P1 ROCK
END OF ROUND 1:
  100% chance; T1P2 & T2P1


ROUND 2:
No team has the advantage, so randomly Team 2 "Strategizes" first.
Team 2 needs no strategy (as there is only 1 player) and will choose randomly between ROCK, PAPER, or SCISSORS
Team 1 recieves no input from Team 1, and only has 1 player, so will also choose randomly between ROCK, PAPER, or SCISSORS
END OF ROUND 2:
50% chance of either team winning

End of match.


I have not worked out all of what this game could expand to, but it seems interesting so far.

