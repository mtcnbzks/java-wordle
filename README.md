# Wordle Game

Wordle is a simple command-line word-guessing game written in Java.

## How to Play

- Clone the repository
- Open the Terminal
- Navigate to the directory where the repository is located
- Compile the program using

```
javac Wordle.java
```

Run the program using:

```
java Wordle
```

Note: The words provided should not exceed the maximum number of tries (6).

### Game Rules

The maximum number of guesses is 6
The length of the input word must be 5
The input word must exist in the dictionary file (src/main/resources/dict.txt)
If the input word contains a letter that exists in the target word, it will show whether the letter is in the right or
wrong position
If the player exceeds the maximum number of tries without guessing the target word, the game ends and displays the key
word.
