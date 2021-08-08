# HANGMAN 
I have implemented a variation of the classic wordgame Hangman. 
For those of you who are unfamiliar with the rules, you may read all about it <a href=https://en.wikipedia.org/wiki/Hangman_(game)>here</a>. In this project, the second player will always be the computer, who will be picking a word at random.
Here are the requirements for your game:

The computer must select a word at random from the list of available words that was provided in words.txt.

<b>The game must be interactive; the flow of the game should go as follows:<b>

<li>At the start of the game, let the user know how many letters the computer's word contains.

<li>Ask the user to supply one guess (i.e. letter) per round.

<li>The user should receive feedback immediately after each guess about whether their guess appears in the computer's word.

After each round, you should also display to the user the partially guessed word so far, as well as letters that the user has not yet guessed.

<b>Some additional rules of the game:<b>
<li>A user is allowed 8 guesses. Make sure to remind the user of how many guesses s/he has left after each round. Assume that players will only ever submit one character at a time (A-Z).

<li>A user loses a guess only when s/he guesses incorrectly.

<li>If the user guesses the same letter twice, do not take away a guess - instead, print a message letting them know they've already guessed that letter and ask them to try again.

The game should end when the user constructs the full word or runs out of guesses. If the player runs out of guesses (s/he "loses"), reveal the word to the user when the game ends.
