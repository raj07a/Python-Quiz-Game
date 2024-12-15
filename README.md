# Python-Quiz-Game
Overview
The Quiz Game is an interactive Python-based project designed to test users' knowledge with a random selection of multiple-choice questions. It features a question bank containing at least 10 questions, out of which 5 are randomly selected for each game session. The game provides instant feedback for each answer and displays the final score upon completion.

This project utilizes file handling for question storage and parsing, ensuring scalability and easy customization.

Features
1. Question Bank
A text file (questions.txt) stores questions, options, and answers.
Each question includes:
The question text.
Four options for users to choose from.
The correct answer indicated by its option number.
Supports a minimum of 10 questions in the bank.
2. Random Question Selection
Selects 5 unique questions randomly from the question bank for each game session.
Ensures no repetition of questions within a single session.
3. Gameplay
Presents multiple-choice questions to the user.
Accepts user input for answers (1/2/3/4).
Provides immediate feedback on whether the answer is correct or incorrect.
Tracks the user’s score throughout the game.
4. Scoring
Awards points for correct answers.
Displays the final score at the end of the game.
Project Architecture
questions.txt: Contains the question bank in the format:
Copy code
Question|Option1,Option2,Option3,Option4|CorrectOptionNumber
quiz_game.py: Main script for game logic and user interaction.
How to Execute the Project
Clone the repository or download the project files.
Ensure Python 3.x is installed on your system.
Prepare the question bank by creating or editing the questions.txt file with the required format.
Run the game script using the command:
Copy code
python quiz_game.py
Follow the on-screen instructions to answer the questions.
Functional Modules
Question Parsing
Reads the question bank file.
Splits and structures data into questions, options, and the correct answer.
Randomization
Utilizes Python’s random module to shuffle questions and ensure variety in each session.
Gameplay Logic
Displays questions and options dynamically.
Collects user input and validates it against the correct answer.
Score Calculation
Increments the score for every correct answer.
Displays the final score and performance summary.


Future Enhancements
Add levels of difficulty (easy, medium, hard).
Integrate a graphical user interface (GUI) using libraries like Tkinter or PyQt.
Store high scores persistently using a database or file.
Expand the question bank dynamically via user submissions.

License
This project is distributed under the MIT License. Feel free to use, modify, and distribute it, subject to the terms of the license.
