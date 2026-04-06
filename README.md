# ai-10x-claude

Guess a number between 1 and 10. And so on. Using Claude Sonnet 4.6.

## Overview

This is a variant of a classic computer game. The computer chooses a hidden random number. You guess what it is. You will be told if you got it right, or you should guess a lower or higher number.

You have a fixed number of guesses for each number. If you don't guess the number within the fixed number of guesses, the game is over and you lose.

## Directions

When you start the game, you will see 1 on the left, and 10 on the right. The computer has picked a random number between 1 and 10 (inclusive). Guess a number. If you guess the number correctly, the game lets you know and starts a new level. If your guess is too high of a number, the higher number on the right will drop, indicating the new highest number. Likewise, if your guess is too low a number, the lower number on the left will raise.

As an example, the game starts with 1 on the left and 10 on the right. You guess 6. As it turns out, that number is bigger than the random number. The numbers on the sides now show 1 and 5. You guess 3. That number is lower - the numbers on the sides show 4 and 5. You guess 4. That's correct - that is the number, and you advance.

There is a entry box below the game. Be sure you are typing into that to enter guesses.

There is a helper. If you guess a number below the left number, or above the right number, it will not be allowed. The guess always needed to be within that range of numbers.

There is another helper. If the left and right numbers share some of the same digits on their left-hand side, those will be pre-entered into the entry box. This is a helper: you would be able to guess any number that didn't start with those digits.

There are nine levels in the game. If you defeat the ninth level, you win! The game is over and you are shown a reward.


## Mobile

This game has support on a mobile tablet. This game is unplayable on a smartphone.

When playing on a tablet, be sure to tap into the entry box below the game. That will enable the keyboard on the tablet. The focus has to be in the entry box to allow the keyboard to be used.

This is unplayable on a smartphone.


## Details

This game will always give you enough turns to guess the number, so long as you play perfectly. You don't need to play perfectly... but you do need to do well.

Fun fact: a simple variation of this game was the very first game I developed as a child.


## From Release #1 (Build 7 on 4/4/26)

* Implements the base version of the game.
  
* Nine levels are supported.
  
* A reward is presented if you defeat the ninth level.
