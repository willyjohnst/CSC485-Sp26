OVERALL TODO
1. Gather Data [X] 
3. Import Data [X]
   - NBA games data
   - Box scores
   Stadium locations
5. Clean/Filter Data [X]
   - keep only NBA games
   - remove preseason, duplicates, and missing outcomes
7. Standardize all variables [X]
8. Merge Datasets [ ]
   - merge games plus attendance by gameID/date
   - merge stadium locations by home/away team
9. Create key variables [ ]
   - ex. attendance, travel distance, back to back, rest days, season and date indicators, time zone
10. Exploratory Data Analysis [ ]
   - Home Win rate overall
   - Home Win rate by attendance
   - Home Win rate by travel
   - Compare rested vs back to back games
11. Statistical Modeling [ ]
    - Logistic Regression
    - Check coefficient signs and significants
12. Robustness Checks [ ]
    - Run models by season and exclude outlier seasons
13. Time Series Analysis [ ]
    - Plot home win percentage by season
    - Test whether home court advantage persists overtime
14. Geographic Analysis [ ]
    - Map stadium locations
    - Visualize win probability vs. travel distance
15. Interpret results [ ]
    - Identify strongest predictors
    - Connect findings back to research questions
16. Finalize Deliverables [ ]
    - Tables, figures, written conclusion
    - Delete gameID and league columns when we are completely done coding


FRIDAY 
- work on games.csv file
-    redirect the winner to a team name instead of an ID
-    get rid of all ID numbers
-    get rid of game type column and clean the columns
-    rename columns to match the stadiums file
COMPLETED ALL and started creating analysis equations and ideas

NEXT WEEK (2/2)
- combine stadiums and games data sets into 1 big data set
- add columns
     - flag back to back games
     - calculate distance traveled
     - take into account time zones
     - prior win/loss streak
     - attendance brackets
     - clearer column showing if home team won or not (0/1 maybe)
- can we break up the data by season so it's not so long


- fix LA Clippers and Lakers
