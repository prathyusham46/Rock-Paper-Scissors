# License
This project is licensed under the MIT License. Feel free to use and modify it as you wish!
You can modify any sections to better fit your project or preferences!

# Rock, Paper, Scissors Game
This is a simple console-based Rock, Paper, Scissors game implemented in Python. The user plays against the computer, and the game keeps track of the number of wins for both the user and the computer.

# Features
- Play Rock, Paper, Scissors against the computer.
- Keep track of wins for the user and the computer.
- Option to quit the game by typing "Q".

# How to Run
1. Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
2. Copy the code into a Python file, e.g., `rock_paper_scissors.py`.
3. Open your command line or terminal.
4. Navigate to the directory where the `rock_paper_scissors.py` file is saved.
5. Run the game by executing the command:
   ```bash
   python rock_paper_scissors.py

# How to Play
When prompted, type either Rock, Paper, or Scissors to make your choice.
To quit the game at any time, type Q.
The computer will randomly choose between Rock, Paper, and Scissors.
The winner of each round will be displayed, and the game will continue until you decide to quit.
At the end of the game, your total wins and the computer's total wins will be displayed.

# Code Overview
-User Input: The program prompts the user to input their choice. If the input is invalid, it will continue to prompt until a valid input is received or the user decides to quit.
-Computer Choice: The computer randomly selects Rock, Paper, or Scissors using the random module.
-Win Conditions: The program checks the user’s choice against the computer’s choice to determine the winner of each round.
-Score Tracking: It keeps track of the number of wins for both the user and the computer and displays the results when the game ends.

