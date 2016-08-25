# Udacity Full Stack Web Development Nanodegree Tournament Project

A python module that uses PostgreSQL database to keep track of players and matches in a game tournament. This module uses Swiss system to pair players in each game.

1. Run this programme using Vagrant Virtual Machine. Navigate to the programme folder and use the command ```vagrant up``` followed by ```vagrant ssh```
2. The main module is ```tournament.py```. ```tournament.sql``` is used to initialize the database structure. ```tournament_test.py``` is used to test the main module.
3. To run the programme:
    a. In Vagrant, open run ```psql``` followed by ```\i tournament.sql``` to initialize the database structure
    b. Run the test using command ```python tournament_test.py```

