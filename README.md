

# The Simple Hangman Game 

This function returns the current state of the hangman figure based on the number of tries left. The `stages` list contains different stages of the hangman figure, starting from no incorrect guesses to the maximum number of incorrect guesses (6 in this case).

 Initializes variables for the word to be guessed (`word`), the current state of the guessed word (`word_completion`), a flag to indicate if the word has been guessed (`guessed`), lists to track guessed letters and words (`guessed_letters` and `guessed_words`), and the number of tries left (`tries`).

The game loop continues until the word is guessed or the player runs out of tries.
If the guess is a single letter, it checks if the letter has already been guessed. If not, it updates the game state based on whether the letter is in the word.
If the guess is the same length as the word, it checks if the word has already been guessed. If not, it updates the game state based on whether the guessed word is correct.
If the guess is invalid, it prompts the player to enter a valid guess.
The hangman figure and the current state of the guessed word are displayed after each guess.
  


