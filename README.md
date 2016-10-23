# Tournament Project

## Introduction
This application uses PostgreSQL database to keep track of players and matches in a game tournament.

The game tournament uses the Swiss system for pairing up players in each round: players are not eliminated, and each player should be paired with another player with the same number of wins, or as close as possible.

This project has two parts: defining the database schema (SQL table definitions), and writing the code that uses it.

## Technologies Used
- PostgreSQL
- Python

## Instructions of Running the App
1. Run this programme using Vagrant Virtual Machine. Navigate to the programme folder and use the command ```vagrant up``` followed by ```vagrant ssh```
2. The main module is ```tournament.py```. ```tournament.sql``` is used to initialize the database structure. ```tournament_test.py``` is used to test the main module.
3. To run the programme:
    a. In Vagrant, open run ```psql``` followed by ```\i tournament.sql``` to initialize the database structure
    b. Run the test using command ```python tournament_test.py```

