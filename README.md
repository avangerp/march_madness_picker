# march_madness_predictor
A **really dumb** bracket picker so I don't have to pretend I know anything about college basketball

### input
A CSV file listing the initial 64 teams in the following format
```
<team1>,<seed>
<team2>,<seed>
<team3>,<seed>
<team4>,<seed>
...
<team64>,<seed>
```
The list of teams must be in order such that `team1` is playing `team2` in the round of 64, and the winner of `team1` and `team2` will play the winner of `team3` vs `team4`, etc.

### Output
a .txt file that walks through which team was chosen in each matchup and why
