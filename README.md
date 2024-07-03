# Kotlin SOS Game README

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Gameplay](#gameplay)
7. [Mark Counter](#mark-counter)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction
Welcome to the Kotlin tictac Game! This is a simple implementation of the classic SOS game, developed using Kotlin. 
## Features

- Adjustable grid size
- Mark counter to keep track of each player's score
- Simple and intuitive UI

## Requirements
- Kotlin 1.5 or higher
- Java Development Kit (JDK) 8 or higher
- An IDE like IntelliJ IDEA or a text editor of your choice

## Installation
1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/kotlin-sos-game.git
    cd kotlin-sos-game
    ```

2. **Open the project:**
   - If you're using IntelliJ IDEA, open the project by selecting `File > Open` and choosing the cloned repository folder.
   - If you're using a text editor, navigate to the project folder and open it.

3. **Build the project:**
   - In   androidstudio IDEA, the project will be built automatically. If not, you can manually build it by selecting `Build > Build Project`.

## Usage
1. **Run the application:**
   - In androidstudio IDEA, run the `main` function in `Main.kt`.
   - If you're using a text editor, compile and run the project using the Kotlin command line tools.

2. **Start playing:**
   - The game will prompt Player 1 to enter their move and the coordinates where they want to place it.
   - The game continues until all cells are filled.

## Gameplay
- **Objective:** Create sequences of "SOS" on the grid.
- **Turns:** Players take turns to place either "S" or "O" on the grid.
- **Winning:** The player with the most SOS sequences when the grid is full wins the game.

## Mark Counter
The mark counter keeps track of the number of SOS sequences each player has created. After each move, the game checks for new SOS sequences and updates the counter accordingly. The current scores are displayed after each turn.


