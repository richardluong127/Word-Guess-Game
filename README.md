# Word-Guess-Game

1. User has 8 guesses to pick the correct letters to make up a word.

2. Computer chooses a random word from the list once game starts.

3. User picks a letter.
    
    - If that letter matches a letter in the word:
        - Display the letter correctly.
        - Change remaining guesses by -1.
        -If that letter is the last missing letter in the word:
             - "Victories" changes by +1. (Victory for singular?)
             - reset the game.

    -If the letter doesn't match a letter in the word:
        - Display the letter in "guesses" section.
        - Change remaining guesses by -1.
        - If the letter is the last guess remaining:
            - "Game Over" changes by +1
            - reset the game.

            