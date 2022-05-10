# bracket-tournament-simulator
The motivation for this work was simple: I wanted to submit a bracket with friends, but I know nothing about the NBA. So, I had a bit of fun and created this fairly simple notebook to simulate tournament results for submitting my bracket.

The mechanics of this simulation are fairly straightforward. For a best-of-7 series, each team is added to a pool 7 times, and then a team name is randomly drawn from the pool 7 times. Weights are used to modify the probability a team name is drawn from the pool. The first team to be picked 4 times is the winner of the round. Thus, all series results are possible (4-0, 4-1, 4-2, 4-3).
