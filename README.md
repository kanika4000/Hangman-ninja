   # THREE -NINJAS-
   # TEAM MEMBERS:-
       1.Kanika:-Manager 
       2.Kirti Vashishat:-Developer 
       3.Mehak Garg:-Tester 
  " The Hangman game is a classic word -guessing game that challenges that can be played by two or more players.The game typically involves a player attempting 
    to guess a letter chosen by another player.The word to be guessed is represented by a row of dashes, each dash representing a letter. The game ends when the 
    guessing player(s) either guess the letter correctly or the complete hangman figure is drawn.If the hangman figure is completed before the word is guessed, the 
     guessing player(s) lose the game.It's a fun and engaging  game that challenges players' vocabulary, deduction, and spelling skills."
   # Objective:-
      One player thinks of a word, phrase, or sentence, and the other player(s) try to guess it by suggesting letters or numbers within a certain number of 
      guesses.
   # Game Play:-
        1. The letter to guess is represented by a row of dashes, with each dash representing a letter or number of the word.
        2. The guessing player suggests a letter.
        3. If the suggested letter occurs in the word, the other player writes it in all its correct positions.
        4. If the suggested letter does not occur in the word, the other player adds one element to a hanged stick figure (or removes an element, depending on the 
        rules).
        5.The game continues until the word is guessed or the stick figure is complete, signifying that all guesses have been used.
   # Rules:-
         Here are the rules for playing the classic game of Hangman:
   # Host Selection:-
         1. Choose one person to be the “host” who creates the puzzle.
         2. The host selects a word and draws the initial hangman figure.
         3. Other players will guess letters to identify the word chosen by the host.
         4. You can take turns being the host or play multiple rounds with the same host.
   # Blank Spaces:-
         1. As the host, draw a blank line for each letter in the word.
         2. For example, if your chosen word is “zipper,” draw six blanks: _ _ _ _ _ _.
         3. Keep the secret word hidden from other players.
   #  Guessing Letters:-
         1. Players take turns guessing letters.
         2. Commonly guessed letters include vowels (“a,” “e,” “i,” “o,” “u”) and frequently used consonants (“s,” “t,” “n”).
   # Filling in Blanks:-
         1. When a player guesses a letter correctly, the host fills in the relevant blank.
         2. For example, if the word is “zipper” and the players guess “e,” the host fills in the 5th blank: _ _ _ _ e _.
      The game can be made easier or harder by adjusting settings.
   # Additional features to be required:-
             1.Difficulty Levels:
                  Implement different difficulty levels (easy, medium, hard) with varying word lengths or limited guesses.
                  Adjust the number of incorrect guesses allowed based on the chosen difficulty level.
             2.Categories and Themes:
                  Allow players to choose from different word categories (e.g., python,Hangman,keyboard,mouse,java).
                  Customize the game theme based on the selected category.
             3.Word Definitions:
                   Display the definition of the secret word after the game ends.
                   This feature can be educational and help players learn new words.
             4.Adding a timer:
                   Once the timer function has been created,it can be added to the hangman game.This can be done by calling the timer function at the start
                   of the game an checking its value at each iteration of game.    
   # Version1:-   
             In this version1,the player does not got the feedback when user the player guess wrong word also there is no user interaction.
             Also,you could add a simple graphical representation of the hangman game.For Example:Different parts of the hangman game for each incorrect
             guess.You can also implement a scoring system by keeping track of the user's guessing time.You can also some time limit.So, the game played by 
             the user is more interesting. You can also add some GUI Enhancement.This addition makes the game more competitive element.So,the player enjoy the 
             hangaman game.
   # Version2:-
             In this version2,the Players may not receive specific feedback on which letters they guessed incorrectly, making it challenging to  
             track their progress and make informed guesses.The game lacks clear instructions or prompts for players, potentially causing confusion about the 
             gameplay rules and objectives.There is no input validation to ensure that players enter only single letters as guesses, which can lead to unexpected 
             behavior or errors.The game interaction is primarily text-based, lacking visual clues or interactive elements that could enhance player engagement 
             and enjoyment.Introduce levels of difficulty, word categories, or additional features to offer a more dynamic and challenging gaming experience.
             This suggestions made the game more interesting and fully enjoyable for the players.
   # Version3:-
             In this version3,"The version3 is much more better than version2" The user Utilizes tkinter to create a user-friendly GUI for the Hangman game,
             enhancing the player's interactive experience.Randomly selects a word from a predefined list for players to guess, adding variability to 
             each game session.Allows players to input a letter guess through an entry widget and check it against the chosen word. It also provides feedback on 
             correct and incorrect guesses by updating the displayed word with correctly guessed letters and reducing the remaining lives accordingly.Displays the 
             number of lives remaining to the player, with a visual representation of the hangman being drawn as lives decrease.It also,notifies the player of 
             winning or losing conditions, showing a congratulatory message upon guessing the word correctly and revealing the word when all lives are exhausted.
             Dynamically draws parts of the hangman figure on the canvas as incorrect guesses accumulate, visually representing the player's progress and mistakes.
             Encourages player engagement through the interactive check button, entry for guesses, and visual feedback on the canvas.Displays informative message 
             boxes using messagebox.showinfo() to inform the player of the game outcome.In this version there is time limit to guess words.so,that the user has to 
             guess words fast and this function makes the game more interesting.This version of the Hangman game offers a basic yet functional gameplay 
             experience with a graphical interface, interactive elements, and feedback mechanisms to engage players in the guessing challenge. Enjoy playing and 
             exploring the hangman game..
