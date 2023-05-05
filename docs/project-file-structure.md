# Project File Structure Strategy:

- Implement a main.py to control gameflow, UI/UX and all gathering of user choice and passing to functionality.

- Seperate modules to contain classes and functions, imported in when needed. 

- Testing directory to separate testing and validation processes from main gameplay

- Log directory to store gameplay history. 
    - Game play should utilize JSON format for smoother implementation and updating within app. 
    - Utilize game-log classes: 
        - Seperate class for global and individual. 
        - Implement composition to include global class as asset of individual? 

