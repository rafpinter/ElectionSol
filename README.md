# ElectionSol

## Plurality election
Pluratily voting is an electoral system in which each voter is allowed to vote for only one candidate, and the candidate who polls more than any other counterpart (a plurality) is elected. (Wikipedia)


### Consideration

At line 21 and 22 we define two global variables for the maximum number of voters and candidates:
```C
// Max number of candidates
#define MAX 9
```
However, if you need more candidates, feel free to increase any number by changing the number 9.


## Runnof election
The two-round system (also known as the second ballot, runoff voting or ballotage) is a voting method used to elect a single winner, where the voter casts a single vote for their chosen candidate. 
Despite its name, the two-round system may resolve an election in a single round if one candidate receives enough of the vote, usually a simple majority. If no candidate receives enough of the vote in the first round, then a second round of voting is held with either just the top two candidates or all candidates who received a certain proportion of the votes. (Wikipedia)


### Consideration

At line 21 and 22 we define two global variables for the maximum number of voters and candidates:
```C
// Max voters and candidates
#define MAX_VOTERS 100
#define MAX_CANDIDATES 9
```
However, if you need more voters or candidates, feel free to increase any number by changing the number 100 or 9.

