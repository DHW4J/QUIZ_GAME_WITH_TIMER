# QUIZ_GAME_WITH_TIMER

## Overview
This Go-based quiz program reads a CSV file containing a list of questions and their corresponding answers, then quizzes the user on those questions. The user is prompted to input their answers to each question, and the program keeps track of the score, displaying the total correct answers at the end.

## Features
- Reads questions and answers from a CSV file.
- Allows the user to input answers.
- Tracks correct answers and provides a final score at the end.

## Requirements
- Go 1.x or higher should be installed on your system.

## How to Run the Program

### 1. Prepare your CSV file
Ensure your CSV file is in the following format:

Each line in the CSV file should contain one question and its corresponding answer, separated by a comma.

Example `problems.csv`:


### 2. Run the program

```bash
go run main.go --csv=path/to/your/csvfile.csv


Problem #1: What is the capital of France? =
Paris
Problem #2: What is 2 + 2? =
4
Problem #3: Who wrote '1984'? =
George Orwell
You scored 3 out of 3

