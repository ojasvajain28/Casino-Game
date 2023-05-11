# Luck Casino Game

Welcome to the Luck Casino Game! This is a simple luck-based casino game implemented in C++. The game allows players to bet on a number between 1 and 10. If their guess matches the rolled dice number, they win 10 times their betting amount. Otherwise, they lose the betting amount. The game continues until the player decides to quit or runs out of money.

## How to Play

To play the Luck Casino Game, follow these steps:

1. Enter your name and starting balance.
2. Read and understand the game rules.
3. Place a bet by entering the betting amount.
4. Guess a number between 1 and 10.
5. If your guess matches the rolled dice number, you win 10 times your betting amount. Otherwise, you lose the betting amount.
6. Your balance is updated accordingly.
7. Repeat steps 3-6 until you decide to quit or run out of money.

## Rules

The rules of the Luck Casino Game are as follows:

1. Choose a number between 1 and 10.
2. If your guessed number matches the rolled dice number, you win 10 times your betting amount.
3. If your guessed number does not match, you lose the betting amount.
4. Your balance is updated based on the outcome of each bet.
5. You cannot bet more than your current balance.

## Requirements

To compile and run the Luck Casino Game, you need:

- C++ compiler
- Standard Library headers (iostream, string)
- C Standard Library headers (cstdlib, ctime)

## Getting Started

To get started with the Luck Casino Game, clone this repository and compile the `main.cpp` file using your C++ compiler. Then, run the compiled executable to start the game.

```shell
$ git clone https://github.com/your-username/luck-casino-game.git
$ cd luck-casino-game
$ g++ main.cpp -o luck-casino-game
$ ./luck-casino-game
