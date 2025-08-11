# 🎯 Number Guessing Game

A simple Python program where the computer picks a random number between 1 and 100, and the user tries to guess it.  
The game gives hints after each guess until you find the correct number.

## 📜 How to Play

1. Run the Python script.
2. The computer will think of a number between **1 and 100**.
3. Enter your guesses one at a time.
4. The program will tell you if your guess is:
   - 📉 Too low
   - 📈 Too high
   - 🎉 Correct!
5. Keep guessing until you win.

## 🖥 Example Gameplay

```
🎯 Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100...
Enter your guess: 50
📈 Too high! Try again.
Enter your guess: 25
📉 Too low! Try again.
Enter your guess: 37
🎉 Correct! You guessed it in 3 attempts.
```

## ⚙ Requirements

- Python 3.x

## ▶ How to Run

1. Save the Python file as `number_guessing_game.py`.
2. Open a terminal or command prompt.
3. Run:
   ```bash
   python number_guessing_game.py
   ```

## 📌 Features

- Random number generation
- Input validation (no crashes on wrong input)
- Unlimited attempts until correct
- Fun feedback messages
