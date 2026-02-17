2/26/2026

Goals for this week:

-[ ] Collect historical NHL player performance data

- [ ] Import and clean salary and slate data

- [ ] Merge datasets into a single modeling table

Last Week's Goals:

- [x] Finalize project scope and assumptions

- [x] Identify data sources (stats + salaries)

- [x] Set up project repository and file structure

Week Reflection: This week I made good progress on collecting and exploring historical NHL player performance data by cleaning the dataset and completing several exploratory analyses, including goals versus ice time, shots on goal, and position-based comparisons. These analyses helped clarify scoring patterns and identify which variables are most informative for evaluating player impact. I did not import or clean salary data and decided that salary will likely not be included in the project going forward. Merging additional datasets and moving toward a unified modeling table will be the focus of the next stage now that the performance data is well understood.


Goals for this week:

- [x] Complete exploratory data analysis (EDA) on key performance variables

- [x] Select a core set of variables for the lineup optimizer

- [x] Write explanations justifying why each variable is included

Last Week’s Goals:

- [x] Collect and clean historical NHL player performance data

- [x] Explore relationships between goals, ice time, shots, and position

- [] Merge datasets into a single modeling table

Week reflection: 
This week I completed the exploratory data analysis on the key performance variables, including examining distributions and relationships between goals, shots, ice time, and position. This helped confirm which variables meaningfully contribute to offensive production and how their effects differ across player roles. I finalized a core set of variables for the lineup optimizer and wrote clear justifications explaining their relevance both statistically and from a hockey perspective.

This weeks goals:

- [x]Built situation specific modeling datasets and prepared per-60 rate statistics for analysis

- [x]Implemented lasso regression with cross-validation to estimate player impact scores

- [x]Compared model performance and interpreted coefficients to understand which variables drive lineup effectiveness

This week I moved from exploratory analysis into formal modeling by implementing lasso regression with cross-validation on situation-specific data. I generated player impact scores and identified which variables most strongly influence performance in different game states. While I had hoped to fully translate these scores into finalized optimized lineups I'm still working on them.

Next weeks goals:
- []Finalize lineup optimization logic for each situation

- []Generate and compare optimized lineups for at least one team across all situations to who those teams usual play

- []Write and interpret the modeling results section, explaining how player scores translate into lineup decisions