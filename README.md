# Fantasy Cricket Game

## Overview

This project is an online fantasy cricket game developed using Python, SQL, SQLite, and PyQt5 technologies. It allows users to create virtual cricket teams, manage player selections, and earn points based on real-time player performances in matches.

### Features

- **User Registration System:** Enables user account creation and management.
- **Player Database:** Includes a comprehensive database of real cricket players with detailed statistics.
- **Team Creation:** Intuitive interface for selecting 11 players within a predefined points limit and category constraints.
- **Real-time Scoring:** Calculates points based on live player performances during matches.
- **GUI:** Developed using PyQt5 for a responsive and user-friendly experience.

### Prerequisites

- Python 3.x
- PyQt5 library
- SQLite3

# Usage

### Creating a New Team

- Click on "New Team" to start creating a new fantasy cricket team.
- Select players from different categories (BATSMEN, BOWLER, ALLROUNDER, WICKETKEEPER) without exceeding the 1000 points limit.
- Save the team data using "Save Team" for future reference.

### Managing Teams

- Use "Open Team" from the "Manage Team" menu to open an existing team.
- Edit or delete teams as needed.

### Scoring and Evaluation

- Calculate points for your fantasy cricket team using "Evaluate Team" from the menu bar.
- Points are awarded based on batting, bowling, and fielding performances of selected players.

### Exiting the Game

- Select "Quit" to exit the game.

## Points Calculation Rules

### Batting

- 1 point for every 2 runs scored.
- Additional 5 points for a half-century.
- Additional 10 points for a century.
- 2 points for a strike rate (runs/balls faced) between 80-100.
- Additional 4 points for a strike rate > 100.
- 1 point for hitting a boundary (four) and 2 points for an over boundary (six).

### Bowling

- 10 points for each wicket taken.
- Additional 5 points for three wickets in an innings.
- Additional 10 points for five wickets or more in an innings.
- 4 points for an economy rate (runs per over) between 3.5 and 4.5.
- 7 points for an economy rate between 2 and 3.5.
- 10 points for an economy rate less than 2.

### Fielding

- 10 points each for catch, stumping, or run out.

![image](https://github.com/shivamanand9009/Fantasy-Cricket-Game/assets/78689810/495fbc3a-94cd-475a-bdeb-761641f1488b)

![image](https://github.com/shivamanand9009/Fantasy-Cricket-Game/assets/78689810/6b8f3b62-ac44-44ef-afaf-97a22be2032f)

![image](https://github.com/shivamanand9009/Fantasy-Cricket-Game/assets/78689810/ab238c3f-f518-4d2e-a888-e242400be902)

![image](https://github.com/shivamanand9009/Fantasy-Cricket-Game/assets/78689810/15b0aa4a-4aa2-42a1-aa9f-2d1c5233945e)



