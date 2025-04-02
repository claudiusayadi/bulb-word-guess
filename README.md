# WordGuess Game

## Overview
WordGuess is a simple console-based word guessing game written in C#. Players attempt to guess words that are contained within a secret sentence, with a limited number of attempts. The game tracks correct guesses and provides feedback after each attempt.

## Features
- Interactive console interface
- Limited attempts (5 guesses)
- Score tracking for correct guesses
- Case-insensitive word matching
- Option to quit early
- Final score and secret sentence reveal

## How to Play
1. Run the program
2. Read the welcome message and instructions
3. Enter a word you think might be in the secret sentence
4. Receive feedback on whether your guess was correct
5. Continue guessing until you run out of attempts (5) or choose to quit
6. View your final score and the complete secret sentence

### Game Rules
- You have 5 attempts to guess words
- Enter '1' at any time to quit the game
- Guesses are case-insensitive (e.g., "You" matches "you")
- Correct guesses increase your score
- The game ends when attempts reach zero or you quit

## Installation
1. Ensure you have .NET installed on your system
2. Clone or download this repository
3. Open the solution in your preferred C# IDE (e.g., JetBrains Rider)
4. Build and run the program

## Sample Output
```bash
Welcome to Word Checker Guessing Game!
    
I have a sentence. You are to guess a word. If the sentence contains that word, you win, if not, you lose.
You have 5 guesses in total!
Enter '1' to exit the game any time.

Guesses left: 5 | Correct Guesses: 0
Enter your guess word:
you
Hurray! 'you' is in the sentence.

Guesses left: 4 | Correct Guesses: 1
Enter your guess word:
cat
Opss...! 'cat' is not in sentence. Try again!

[...]

=== Game Over ===
You guessed 3 words correctly!
The sentence is 'When you pursue your Personal legend, the whole universe conspires to help you achieve it'.
```

## Future Improvements
- Add input validation for empty guesses
- Implement difficulty levels with different sentences
- Add hints system
- Track and display high scores
- Add color to console output

## License
This project is open-source and available under the MIT License.
