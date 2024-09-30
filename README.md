# Football Midfielder Clustering with K-Means

## Introduction
This project aims to group midfielders in football with similar playing characteristics using K-Means clustering. By clustering midfielders based on their key performance indicators (KPIs), we can identify distinct profiles or styles of play, which can be used by scouts, coaches, and analysts to make informed decisions about player recruitment, development, and tactics.

This analysis helps to categorize midfielders into groups that reflect different roles or playing styles, such as defensive midfielders, box-to-box, deep-lying playmakers, or attacking midfielders.

## Metrics Used
The metrics used for clustering include various performance indicators that characterize different aspects of a midfielder's play style:

- **Player**: Player name
- **Min**: Minutes played
- **Gls**: Goals scored
- **Ast**: Assists
- **xG**: Expected goals
- **xAG**: Expected assists from goals
- **Progressive Carries**: Number of times the ball was carried significantly forward
- **Progressive Passes**: Passes that move the ball significantly forward
- **Crosses into Penalty Area**: Crosses delivered into the opponent's penalty area
- **Key Passes**: Passes leading directly to a shot
- **Long Passes Attempted**: Number of long passes attempted by the player
- **Medium Passes Attempted**: Number of medium-range passes attempted
- **Passes into Final Third**: Passes completed into the opponent's final third
- **Passes into Penalty Area**: Passes completed into the opponent's penalty area
- **Progressive Passing Distance**: Total distance covered by forward-moving passes
- **Short Passes Attempted**: Number of short passes attempted
- **Total Passing Distance**: Total distance covered by all passes
- **xA**: Expected assists
- **Through Balls**: Passes splitting the defense to a teammate
- **Clearances**: Defensive actions clearing the ball away from the goal area
- **Interceptions**: Defensive actions intercepting an opponent's pass
- **Tackles**: Number of tackles made
- **Total Blocks**: Number of times a player blocked the ball, including passes and shots

These metrics provide a comprehensive overview of a midfielder's playing style, both offensively and defensively.

## Requirements
To run this project, the following dependencies are needed:

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

