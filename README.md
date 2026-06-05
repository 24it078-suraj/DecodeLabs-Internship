# DecodeLabs Java Internship — Project 1
## Number Guessing Game

**Batch:** 2026  
**Organization:** DecodeLabs  
**Language:** Java  

---

## About The Project
🎯 Number Guessing Game (Java):
A simple, interactive Number Guessing Game built in Java. This project demonstrates core Java programming concepts such as loops, conditionals, user input handling, exception handling, and basic game logic.

## 📌 Project Overview
This application generates a random number between 1 and 100, and the player must guess it within a limited number of attempts.
The game tracks:

Number of attempts
Score per round
Total score across multiple rounds


## 🚀 Features

✅ Random number generation (java.util.Random)
✅ Interactive user input (java.util.Scanner)
✅ Input validation & error handling
✅ Multiple game rounds
✅ Scoring system based on performance
✅ Replay option
✅ Clean console UI with banners and results


## 🎮 How to Play

The game will generate a random number between 1 and 100.
You get 10 attempts to guess the number.
After each guess:

You’ll receive feedback (too high / too low).


If you guess correctly:

You earn a score (higher score for fewer attempts).


After the round ends:

You can choose to play again.




## 🧠 Scoring System

Base score: 100 points
Penalty: 10 points per extra attempt
Minimum score for a win: 10 points
If you lose: 0 points


##🛠️ Technologies Used

Java (JDK 8 or higher)
Standard Libraries:

java.util.Random
java.util.Scanner




## 📂 Project Structure
DecodeLabs_Java_P1.java
README.md


## ▶️ How to Run
1. Compile the program
Shelljavac DecodeLabs_Java_P1.javaShow more lines
2. Run the program
Shelljava DecodeLabs_Java_P1Show more lines

## 🧩 Key Methods


playRound()
Handles one complete game round including guessing and score calculation. [aktuacin-m...epoint.com]


askPlayAgain()
Prompts the user to continue or exit. [aktuacin-m...epoint.com]


printBanner()
Displays the welcome message. [aktuacin-m...epoint.com]


printSummary()
Shows total rounds and score at the end. [aktuacin-m...epoint.com]



## 🎯 Learning Outcomes
This project helps you understand:

Control flow (loops, if-else)
User interaction in console applications
Game logic design
Code organization using methods
Basic scoring algorithms


## 👨‍💻 Author

DecodeLabs Intern
Batch 2026


## 📜 License
This project is open-source and free to use for learning purposes.

## ⭐ Contribute / Feedback
Feel free to fork this repository, improve the game, and submit pull requests!
