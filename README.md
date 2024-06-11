A/B Testing Analysis for Cookie Cats
Introduction
Cookie Cats is a popular mobile puzzle game developed by Tactile Entertainment. 
It’s a classic “connect three” game where players must match tiles of the same color to clear the board and win levels.
As players progress, they encounter gates that prompt them to wait or make an in-app purchase to continue. 
This A/B test aims to analyze the impact of moving the first gate from level 30 to level 40 on player retention.

Problem Statement
The primary goal is to determine whether moving the gate affects the 1-day and 7-day retention rates of players.

Data Dictionary
userid: Unique identifier for each player.
version: Indicates control group (gate_30) or test group (gate_40).
sum_gamerounds: Total game rounds played by the player in the first 14 days after installation.
retention_1: Indicates if the player returned 1 day after installing.
retention_7: Indicates if the player returned 7 days after installing.
Methodology
The A/B test was conducted by randomly assigning players to two groups: one experienced the gate at level 30, and the other at level 40.
Player retention was measured at 1-day and 7-day intervals.
Statistical tests (e.g., chi-squared test, Bayesian analysis) were used to evaluate the results.
Results
1-day retention: Slight decrease when the gate was moved, but not statistically significant.
7-day retention: Noticeable decrease when the gate was moved, with statistical significance.
Conclusion
The A/B test provides strong evidence that the 7-day retention is higher when the gate is at level 30.
Therefore, it is recommended not to move the gate from level 30 to level 40 to maintain higher retention rates.

Recommendations
Further research could involve collecting player feedback through surveys to understand the reasons behind the retention rates.
Additional A/B tests could be conducted to explore other game elements that might impact player retention.
