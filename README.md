# Word-Guessing-Game
Client server word guessing game with microservice wordbank

To Run:

In the SRC folder type: java server.java 5599

In a second shell, in the SRC folder type: java client.java localhost 5599

You are now connected to a game.

On the client, arguments are: startGame, quit, help, endGame, restartGame, guessLetter, guessPhrase, addWord, removeWord, checkWord

Start a new game with "startGame" "gamename" "number of words" "number of guesses"

To make a guess, you would type "guessLetter" "gamename" "letter".

Points are awarded based on solving the word and guessing the correct letter, at the end of the game your score and the correct word will be displayed.
