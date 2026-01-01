# Rock Paper Scissors Game (Python)

## Overview

This project is a **menu-driven Rock–Paper–Scissors game** implemented in **Python**. It supports both **Single Player (User vs Computer)** and **Double Player (User vs Friend)** modes using simple conditional logic and random choice generation.

The game runs in a loop until the user chooses to exit.

---

## Game Modes

### Single Player Mode

* Player plays against the computer
* Computer randomly chooses between Rock, Paper, or Scissor
* Winner is decided using standard game rules

### Double Player Mode

* Two human players play against each other
* Both players enter their choices manually
* Result is displayed instantly

### Exit

* Terminates the game loop

---

## Rules of the Game

* Rock beats Scissor
* Scissor beats Paper
* Paper beats Rock
* Same choices result in a draw

---

## Technologies Used

* Python 3
* `random` module
* Conditional statements
* Loops and lists

---

## Project Structure

```
Rock-Paper-Scissors/
│
├── rps_game.py     # Main game file
├── README.md      # Project documentation
```

---

## How to Run the Game

### Prerequisites

* Python 3 installed on your system

### Run Command

```bash
python rps_game.py
```

---

## Code Logic Explanation

* A list stores valid choices: `rock`, `paper`, `scissor`
* Menu is displayed using a `while` loop
* User selects game mode using numeric input
* In single-player mode, the computer makes a random choice
* Conditional statements determine the winner

---

## Sample Output

```
==========MENU==========
1.Single player
2.Double player
3.Exit

My turn:: rock
Computer's turn:: paper
Computer win
```

---

## Learning Outcomes

* Understanding loops and conditionals
* Using Python lists and strings
* Working with the `random` module
* Building menu-driven console applications

---

## Future Improvements

* Input validation (uppercase/lowercase handling)
* Score tracking system
* Replay option per round
* GUI version using Tkinter

---

## Author

Gauri
