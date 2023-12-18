# Premier League Review of the Season 2022/2023
![6](https://github.com/Sabacon/Premier-League-2022_23-Season-in-Review/assets/121859090/f3bcc7d8-d2a2-4d7d-a95e-859cd39bd70d)

### Problem definition/ Task
Key results and statistics from the EPL 2022/23 season may be readily apparent to the keen supporter of English football. But even those of us who live and breathe football need a closer examination of the numbers after the fact is necessary to understand the full picture. Therefore, this is a data analysis project.

### Project goals
This project aims to uncover the numbers that defined the season.

### Project scope
This is a data analysis project with a bit of visualization. Machine Learning will not be used as I will not predict game outcomes. Analysis of trends and expected metrics (xG, npxG, xGA, xPTS, etc) is also beyond the scope of this project.

**Tools:**
* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Jupyter notebooks

### The Data
I used the Premier League dataset from Kaggle. It is provided in this repository alongside the .ipynb file.

* Used `string functions` to fix the inconsistencies in the column names
* I converted the `date` column to a `datetime` index
* Converted the figures in the `attendance` column into `integers`
* Did a Google Search to fill in the Nan values in the `attendance` column
* Filled in the Nan values in the `Stadium` column with the correct stadium names
* Dropped the `links` column as it won't be of any use in this project

### Questions Answered
1. What were the total attendance figures?
2. What was the average attendance per match?
3. Which match drew the biggest crowd?
4. Which game was attended by the fewest people?
5. At what time did most of the matches kick-off?
6. What was the mean attendance per kick-off time?
7. How many goals were scored?
8. How many goals were scored on average per game?
9. Are the goals normally distributed?
10. How many goals were scored by the home and away teams?
11. WhIch teams were involved in the highest-scoring game?
12. What was the biggest margin of victory? Which team was on the end of that particular drubbing?
13. What were the 5 biggest home and away wins?
14. How many barren draws?
15. What was the highest-scoring draw?
16. How many goals were scored on average per kickoff time?
17. Which teams scored the most goals?
18. Which teams found the net on the fewest occasions?
19. Who had the best and worst conversion rates?
20. Which teams received the most bookings?
21. Which teams went the entire season without a sending-off?
22. In how many matches was the home team victorious?
23. How many matches ended in an away win?
24. How many games were tied?
25. What was the highest ball possession in a single home match?
26. Which teams had the highest ball possession on enemy territory?
27. Which teams had the most goal attempts in a single home match?
28. Which teams had the most goal attempts in a single away match?
29. How many yellow cards were brandished in the entire season and on average per match?
30. How many early showers were taken during the season?
31. What were the top 5 dirtiest clashes?
32. How many players were booked in the dirtiest clash?
33. How did the top 6 teams fare against each other?
