# 8086 Guessing Game

## Project Overview
This project is an Assembly Language guessing game developed for the 8086 microprocessor. The game prompts the user to guess a number between 1 and 255 and provides feedback on whether the guess is too high, too low, or correct. The program includes input validation to ensure that the user input is within the valid range and is not more than three digits long.

## How It Works
1. **Input Prompt**: The program asks the user to guess a number between 1 and 255.
2. **Input Validation**: Checks if the input is:
   - Not more than three digits.
   - Within the range of 1 to 255.
3. **Feedback**: Based on the input, the program displays:
   - "The number is bigger than your guess" if the guessed number is too low.
   - "The number is smaller than your guess" if the guessed number is too high.
   - "Out of range number" if the input is not within the valid range.
   - "You have made a fine guess" if the guessed number is correct.
4. **Replay Option**: After a correct guess, the user is asked if they want to play again (y/n).

## Files Included
- `8086_Guessing_Game.asm`: The main assembly source code for the guessing game.
- `PROJECT_PRESENT.pptx`: A presentation providing an overview and working procedure of the project.

## Getting Started
To run the project, you need an assembler that supports 8086 assembly language. Here are the steps to assemble and run the program:

1. Assemble the code using an assembler like NASM or MASM.
   ```bash
   nasm -f bin 8086_Guessing_Game.asm -o 8086_Guessing_Game.com
