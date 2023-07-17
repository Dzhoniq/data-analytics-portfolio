Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three"-style puzzle game where the player must connect tiles of the same color to clear the board and win the level. 

As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.

But where should the gates be placed? Initially the first gate was placed at level 30, but in this notebook we're going to analyze an AB-test where we moved the first gate in Cookie Cats from level 30 to level 40. In particular, we will look at the impact on player retention. But before we get to that, a key step before undertaking any analysis is understanding the data. 

# Project 1: "Cookie Cats" game's retention analysis using AB-test 
## Project Overview:
Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three"-style puzzle game where the player must connect tiles of the same color to clear the board and win the level. 

As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.

But where should the gates be placed? Initially the first gate was placed at level 30, but in this notebook we analyzed an AB-test where we moved the first gate in Cookie Cats from level 30 to level 40. In particular, we looked at the impact on player retention. 

## Installation and Setup
To work on this project, download CSV file under the folder.
If you download jupyter noteboook (ipynb) in the folder, you can see the the description, tasks and step-by-step analysis with the python script. 

## Codes and Resources Used
 - Python was used for this project
 - Python libraries: (Numpy, Pandas, Seaborn, Matplotlib)

## Technial skills 
- Python
- Data Acquisition: upload csv file
- Data Preprocessing
-   Data Cleaning
-   Data Validation
-   Exploratory Data Analysis (EDA)
-   Descriptive and Inferential Statistics
-   Data Visualization to support/check my findings with the audience
-   Hypothesis testing


## Results and Evaluation 
The bootstrap result tells us that there is strong evidence that 7-day retention is higher when the gate is at level 30 than when it is at level 40. The conclusion is: If we want to keep retention high — both 1-day and 7-day retention — we should <strong>not</strong> move the gate from level 30 to level 40. There are, of course, other metrics we could look at, like the number of game rounds played or how much in-game purchases are made by the two AB-groups. But retention <em>is</em> one of the most important metrics. If we don't retain our player base, it doesn't matter how much money they spend in-game.
