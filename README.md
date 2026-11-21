# Rock Paper Scissors

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Game](https://img.shields.io/badge/type-terminal%20game-lightgrey)

A terminal game where you play rock, paper, scissors against the computer. The first side to score 10 points wins.

## Gameplay

Each round collects a player move, generates a computer move, compares both choices, and updates the score. A tie does not award a point. The match continues until a player reaches the target score.

## Architecture

Terminal input → move validation/selection → round comparison → score update → next round or match result

The game is a single Python script and uses no network service or external package.

## Start locally

Install Python 3 and launch the script from a terminal:

    python RockPaperScissors.py

Follow the prompts to enter a move. Run the command from the repository directory so Python can find the script.

## Project layout

- RockPaperScissors.py — game loop, input, computer choice, round result, and score tracking
- README.md — project and run instructions

## Limitations

The game is command-line only. It does not include a graphical interface, saved match history, online multiplayer, or automated tests. No license file is listed in the repository.