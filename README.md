# Cricket Data Analytics

## Overview
The Cricket Data Analytics project aims to identify the optimal 11 players capable of averaging 180 runs scored and defending an average of 150 runs. This analysis provides valuable insights for team selection, maximizing performance in competitive cricket.

## Problem Statement
The challenge is to find the best 11 players who meet specific performance criteria that ensure a successful batting and bowling strategy.

## Player Selection Criteria

### 1. Top-Order
- **Batting Average:** > 30
- **Strike Rate:** > 140
- **Innings Batted:** > 3
- **Boundary Percentage:** > 50
- **Batting Position:** < 4

### 2. Middle Order
- **Batting Average:** > 40
- **Strike Rate:** > 125
- **Innings Batted:** > 3
- **Average Balls Faced:** > 20
- **Batting Position:** > 2

### 3. Finishers
- **Batting Average:** > 25
- **Strike Rate:** > 130
- **Innings Batted:** > 3
- **Average Balls Faced:** > 12
- **Batting Position:** > 4
- **Innings Bowled:** > 1

### 4. All-rounders
- **Batting Average:** > 15
- **Strike Rate:** > 140
- **Innings Batted:** > 2
- **Batting Position:** > 4
- **Innings Bowled:** > 2
- **Bowling Economy:** < 7
- **Bowling Strike Rate:** < 20

### 5. Bowlers
- **Innings Bowled:** > 4
- **Bowling Economy:** < 7
- **Bowling Strike Rate:** < 16
- **Bowling Average:** < 20
- **Dot Ball Percentage:** > 40

## Data Sources and Tools

- **Web Scraping:** Data was gathered from ESPN Cricinfo using Python's Beautiful Soup.
- **Data Cleaning & Transformation:** Python Pandas was utilized for cleaning and transforming the data.
- **Data Transformation:** Power Query was employed for data transformation tasks.
- **Data Modeling:** Parameters were built using DAX for effective data modeling.

## Conclusion
This project provides a comprehensive analysis of cricket player performance, aiding in the strategic selection of players to optimize team performance based on historical data. 

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or feedback, feel free to reach out:

Name: Anup
Email: anupddas8@gmail.com
